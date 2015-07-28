# tei-style-dta-context
ConTeXt environment to typeset XML (TEI P5) from Deutsches Textarchiv

This is a fun project to learn more about the capabilities of ConTeXt to typeset XML sources.
The ConTeXt environment `tei-style.tex` can be used to typeset XML (TEI P5) files. Just download a XML file from
[www.deutsches-textarchiv.de](http://www.deutsches-textarchiv.de) and process it like this:

    contextjit --environment=tei-style.tex file.xml

With `--mode=orginal` the book is typeset with the orginal linebreaks from the scanned edition.

    contextjit --environment=tei-style.tex --mode=original file.xml

With `--mode=fraktur` the book is typeset with Fraktur font.

The environment is far from being perfect. In fact it only has the most basic features.
