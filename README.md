Takes any PDF and turns it into a book form (A5 pages on A4 paper). The resulting PDFs are printed in duplex (long-edge flip, which is usually the default).

# Making chapbooks

    chapbook.sh input.pdf output.pdf

Chapbooks are then simply folded in half. The best page length for chapbooks is 16 pages. Above 24 starts to become unweildly without trimming and securing the pages. Folded chapbooks can be stapled or sewn.

Hamish MacDonald made a video tutorial on how to make "a simple chapbook":http://www.hamishmacdonald.com/books/books/DIYbook_ep16.php

# Making perfect bound books

    book.sh input.pdf output.pdf

Books are designed to be perfect bound with 1 sheet signatures. To do this, fold each page in half, stack the pages together, and glue.

Hamish MacDonald made a tutorial on "perfect bound books.":http://www.hamishmacdonald.com/books/books/DIYbook_ep17.php

## Dependencies

Relies on ConTeXt and its pdftrimwhite.pl script, which relies on ghostscript

## Installation

Put the .sh files in your path.

Set PDFTRIMWHITE to the location of your pdftrimwhite.pl file. For Mac installs of TexLive (2011) the location is:

    PDFTRIMWHITE=/usr/local/texlive/2011/texmf-dist/scripts/context/perl/pdftrimwhite.pl
