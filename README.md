# Islandora Sample Objects

This sample set of objects and corresponding metadata has been organized by object types.
You may ingest these objects into any Islandora installation.
These objects are provided both in raw and zipped formats: raw enables you to view the files; the zipped version is typically how you would ingest into Islandora.

Islandora contains Drupal modules called Islandora Solution Packs and they interact with file objects (like this set of samples) in the following manner:

> Solution Packs present a starting point for users with particular types of data, such as books or audio files. A solution pack will allow users to ingest and edit a particular type of content, including derivatives and metadata. A solution pack also provides a default empty collection for users, configured for that type of content. [source](https://wiki.duraspace.org/display/ISLANDORA/Solution+Packs)

## Content Models Provided (1, 2 or 3 samples of each)

* AUDIO
* BASIC_IMAGE
* BOOK
* LARGE_IMAGE
* PDF
* VIDEO
* COMPOUND_OBJECT
    * This sample also includes one BINARY object and an IMI-compatible CSV file for import, along with a sample TWIG template to engage IMI.  
* WEB_ARCHIVE
* ORAL_HISTORY

## Seeking contributions of samples for these content models

* Disk Image
* Entities
* Islandora Paged Content
* Newspaper

## Future Work:

* Create a Twig template for using the [Islandora Multi Importer](https://github.com/mnylc/islandora_multi_importer) (IMI) to bulk import this sample set of objects and metadata into Islandora.
    * Note that the COMPOUND_OBJECT sample now includes an IMI .twig template and .csv file for this purpose.

## Contact Us
* If you have questions, please contact [David Keiser-Clark](dwk2@williams.edu) or post to the [Islandora google group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/islandora/topics)

## See Also: Advanced tools to dynamically generate sample content
* [Islandora Sample Content Generator](https://github.com/mjordan/islandora_scg) - Uses Drush on the commandline to generate objects
* [Ten Million with a Hat](https://github.com/discoverygarden/ten_million_with_a_hat) - Adds a drush commandline script for ingesting many objects; say, ten million.
