# EDSL as a platform

This project is intended to be a ready-made platform for publishing
texts in several formats, including printed versions.

It includes all Jekyll layouts and plugins used by [En Defensa del
Software Libre](https://endefensadelsl.org).

Just fork and add your Jekyll template!

## Features

* Publishes articles in any format supported by pandoc.

* Publishes documents bundling articles by category.

* Provides an OPDS catalog to allow download of epubs from an ebook
  reader.

* Provides ready from print PDF files.

* Provides a full feed with links to other formats download.

* Creates a torrent file for the whole site.

## Customizing

Files that need modifications:

* `_config.yml` of course.

* `_layouts/default.html` this file includes the default article
  template, but currently just includes some things and no design at
  all.

* `_layouts/license.tex` the license page on your PDF files.  You'll
  want to modify this.

## Post metadata

* `cover` an image that's the book cover.

* `license` the license URL.

* `category` if you want to bundle articles on single documents, put
  them on the same category.
