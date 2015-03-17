Project goal: convert images/zip-files from manga/comic into valid format for Amazon Kindle v4!


The format will be CBZ (http://en.wikipedia.org/wiki/Comic_book_archive) which the Kindle is able to handle and CBC, which are several CBZ in one file.
With Calibre (http://manual.calibre-ebook.com/) you can convert the CBC file into a format for the Kindle.

Update 11.12.2011: It will support the epub format via this Library: http://www.siegmann.nl/epublib/android
And with KindleGen convert it to MOBI-format (http://www.amazon.com/gp/feature.html?docId=1000234621)



Until Step 3, the source will be hosted on my private SVN!

Timeline:
  * Step 1: CommandLineInterface (22% @ December 16th 2011)
  * Step 2: read from zipped Files (many portals offers zip-downloads from the mangas)
  * Step 3: GUI (not everyone is happy with a CLI version)
  * Step 4: every kindle format + probably other e-readers (no use for Calibre then)
  * Step 5: direct download from manga portals (with template configs for each site and not fixed builtin)


The program will be written in JAVA -> so every OS can run it without any frustrations, because i was not able to run the latest version from Mangle (http://foosoft.net/mangle/) at my MacBookAir...