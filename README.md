# Islandora Sample Objects

This sample set of objects and corresponding metadata has been organized by object types.
You may ingest these objects into any Islandora installation.
These objects are provided both in raw and zipped formats: raw enables you to view the files; the zipped version is typically how you would ingest into Islandora.

Islandora contains Drupal modules called Islandora Solution Packs and they interact with file objects (like this set of samples) in the following manner:

> Solution Packs present a starting point for users with particular types of data, such as books or audio files. A solution pack will allow users to ingest and edit a particular type of content, including derivatives and metadata. A solution pack also provides a default empty collection for users, configured for that type of content. [source](https://wiki.duraspace.org/display/ISLANDORA/Solution+Packs)

Included is a generic Twig template ("DGMaster.twig") for using the [Islandora Multi Importer](https://github.com/mnylc/islandora_multi_importer) (IMI) to bulk import this sample set of objects and metadata into your Islandora stack. Also included is a Twig template ("Compound.twig" and .csv file) within the COMPOUND_OBJECT sample specifically for compound objects.

## Content Models Provided (1, 2 or 3 samples of each)

* AUDIO
* BASIC_IMAGE
* BOOK
* COMPOUND_OBJECT
    * This sample also includes one BINARY object and an IMI-compatible CSV file for import, along with a sample TWIG template to engage IMI.  
* LARGE_IMAGE
* NEWSPAPERS
* ORAL_HISTORY
* PDF
* VIDEO
* WEB_ARCHIVE

## Seeking contributions of samples for these content models

* Disk Image
* Entities

## Future Work:

Question: Possibly more polish for the Twig templates?

## Contact Us
* If you have questions, please contact [David Keiser-Clark](dwk2@williams.edu) or post to the [Islandora google group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/islandora/topics)

## See Also: Advanced tools to dynamically generate sample content
* [Islandora Sample Content Generator](https://github.com/mjordan/islandora_scg) - Uses Drush on the commandline to generate objects
* [Ten Million with a Hat](https://github.com/discoverygarden/ten_million_with_a_hat) - Adds a Drush commandline script for ingesting many objects; say, ten million.
