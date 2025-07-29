# guidelines-data

XML data of the new encoding guidelines to go with [https://github.com/BetaMasaheft/guidelinesApp]

files originally in the [Documentation wiki](https://github.com/BetaMasaheft/Documentation/wiki/guidelines) converted from markdown to TEI Simple using Pandoc then transformed to better use the encoding of [TEI documentations tags](http://www.tei-c.org/release/doc/tei-p5-doc/de/html/TD.html#TDphrase)

- files in the elements collection are created with xslt from `listelements.xml`
- files in the pages collection are created with xslt from the initial pandoc output
- files in the toc collection are minimal tei files with a list of items pointing to pages
- the schema is a minimal implementation to validate these files which are synced to the server
