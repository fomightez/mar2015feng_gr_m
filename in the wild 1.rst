.. contents::
   :depth: 3.0
..

Examples from the Wild I: REGULAR EXPRESSIONS
=============================================

NGS Analysis of ChIP-seq data with NUCwave
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`ChIP-Seq example at NUCwave
site <http://nucleosome.usal.es/nucwave/#example-4-chip-seq-single-reads>`__
> S. cerevisiae reference genome was downloaded from SGD and FASTA
headers for chromosome names were replaced with chrI-chrXVI.

Of course, there are only sixteen chromosomes in yeast, plus the
mitochondrial genome, so this is not an overly difficult to do by hand.
But it is tedious and offers a good place to utilize regular
expressions.

Highly recommend the following combination for learning Regular
Expressions, or ``Regex`` or ``Regexp`` as it is often called:

-  `Chapters 2 & 3 of Practical Computing for Biologists book by Haddock
   and Dunn <http://practicalcomputing.org/>`__. The related appendix #2
   is freely available as part of `tables of Appendices from Practical
   Computing for Biologists book by Haddock and
   Dunn <http://practicalcomputing.org/files/PCfB_Appendices.pdf>`__

-  `Regular Expressions
   Primer <http://www.ternent.com/tech/regexp.html>`__

-  `Regular Expressions 101: online regex editor and debugger
   tool <https://regex101.com/>`__ (This seems best with ``g`` global
   modifier on.)

First I'll demonstrate doing this with Sublime Text using `the process I
already worked
out <https://gist.github.com/fomightez/2e31e3e7afcd54d18229>`__.

So what are ``Regular Expressions``? Exploring with `Regular Expressions
101 <https://regex101.com/>`__.

wildcards, character sets, qantifiers and capturing.

Finally, we'll use `Regular Expressions 101 <https://regex101.com/>`__
to really follow what was going on in this
`example <https://gist.github.com/fomightez/2e31e3e7afcd54d18229>`__.
