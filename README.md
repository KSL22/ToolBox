ToolBox
=======

Various scripts for bioinformatics/phyloinformatics/etc that I've put together/stollen/borrowed over time

I've provided attribution where I can remember I took code bits from somewhere. If there's something that's your's I'm happy to add attribution or take it down if I accidentally violated the license.

Some description of the scripts:

* **BLASTPaser.pl** -- is a simple parser for BLAST output. The script is based on the [BioPerl SearchIO tutorial](http://www.bioperl.org/wiki/HOWTO:SearchIO).

* **BLASTParser_table.pl** -- is the same as above, but for tabular BLAST output.

* **clean_blank_taxa.pl** -- a script to remove taxa from a phylip file that have no data. Often when a multigene dataset is split into the individual genes, there are taxa which don't have data for some genes. These cause problems in the analysis, so this removs them.

* **MFAtoPHY.pl** -- a handy script from [Yu-Wei Wu](http://yuweibioinfo.blogspot.com/2009/01/fasta-to-phylip-converter.html) to convert a fasta file to a phylip file.



