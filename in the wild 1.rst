.. contents::
   :depth: 3.0
..

Examples from the Wild I: REGULAR EXPRESSIONS
=============================================

Methods sections are good for finding what others used and then now you
can use

NGS Analysis of ChIP-seq data with NUCwave
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`ChIP-Seq example at NUCwave
site <http://nucleosome.usal.es/nucwave/#example-4-chip-seq-single-reads>`__
> S. cerevisiae reference genome was downloaded from SGD and FASTA
headers for chromosome names were replaced with chrI-chrXVI.

Of course, there are only sixteen chromosomes in yeast, plus the
mitochondrial genome, so this not overly difficult to do by hand. But it
is tedious and offers a good place to utilize regular expressions.
