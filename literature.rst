.. contents::
   :depth: 3.0
..

Literature Selections for ChIP-seq
----------------------------------

ChIP-Seq
~~~~~~~~

-  `Lefrançois P1, Euskirchen GM, Auerbach RK, Rozowsky J, Gibson T,
   Yellman CM, Gerstein M, Snyder M. Efficient yeast ChIP-Seq using
   multiplex short-read DNA sequencing. BMC Genomics. 2009 Jan 21;10:37.
   doi:
   10.1186/1471-2164-10-37. <http://www.ncbi.nlm.nih.gov/pubmed/19159457>`__

    We used this method to map the binding sites for Cse4, Ste12 and Pol
    II throughout the yeast genome and we found 148 binding targets for
    Cse4, 823 targets for Ste12 and 2508 targets for PolII. Cse4 was
    strongly bound to all yeast centromeres as expected and the
    remaining non-centromeric t

-  `Feng J, Liu T, Qin B, Zhang Y, Liu XS. 2012. Identifying ChIP-seq
   enrichment using MACS.Nat Protoc. 2012 Sep; 7(9):
   10.1038/nprot.2012.101. <http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3868217/>`__

    MACS is coded in Python, an increasingly popular programming
    language in bioinformatics, which is pre-loaded with the majority of
    UNIX, Linux, or Mac OS installations. MACS works in Python version
    2.6 or 2.7, and version 2.6.5 is recommended. To run MACS in a
    64-bit environment, Python for the 64-bit CPU should be installed.

-  `Use model-based Analysis of ChIP-Seq (MACS) to analyze short reads
   generated by sequencing protein-DNA interactions in embryonic stem
   cells. Liu T. Methods Mol Biol. 2014;1150:81-95. doi:
   10.1007/978-1-4939-0512-6\_4. <http://www.ncbi.nlm.nih.gov/pubmed/24743991>`__

-  `ChIP-seq guidelines and practices of the ENCODE and modENCODE
   consortia. Landt SG, Marinov GK, Kundaje A, Kheradpour P, Pauli F,
   Batzoglou S, Bernstein BE, Bickel P, Brown JB, Cayting P, Chen Y,
   DeSalvo G, Epstein C, Fisher-Aylor KI, Euskirchen G, Gerstein M,
   Gertz J, Hartemink AJ, Hoffman MM, Iyer VR, Jung YL, Karmakar S,
   Kellis M, Kharchenko PV, Li Q, Liu T, Liu XS, Ma L, Milosavljevic A,
   Myers RM, Park PJ, Pazin MJ, Perry MD, Raha D, Reddy TE, Rozowsky J,
   Shoresh N, Sidow A, Slattery M, Stamatoyannopoulos JA, Tolstorukov
   MY, White KP, Xi S, Farnham PJ, Lieb JD, Wold BJ, Snyder M. Genome
   Res. 2012 Sep;22(9):1813-31. doi: 10.1101/gr.136184.111. PMID:
   2295599 <http://www.ncbi.nlm.nih.gov/pubmed/22955991>`__

-  `Bailey T, Krajewski P, Ladunga I, Lefebvre C, Li Q, et al. (2013)
   Practical Guidelines for the Comprehensive Analysis of ChIP-seq Data.
   PLoS Comput Biol 9(11): e1003326.
   doi:10.1371/journal.pcbi.1003326 <http://www.ncbi.nlm.nih.gov/pubmed/24244136>`__

-  `ChIP-Seq: technical considerations for obtaining high-quality data.
   Kidder BL, Hu G, Zhao K. Nat Immunol. 2011 Sep 20;12(10):918-22. doi:
   10.1038/ni.2117. PMID:
   21934668 <http://www.ncbi.nlm.nih.gov/pubmed/21934668>`__

-  `Integrative analysis of public ChIP-seq experiments reveals a
   complex multi-cell regulatory landscape. Nucleic Acids Res. 2015 Feb
   27;43(4):e27. doi: 10.1093/nar/gku1280. Epub 2014 Dec 3. Griffon A,
   Barbier Q1, Dalino J, van Helden J, Spicuglia S, Ballester B. PMID:
   25477382 <http://www.ncbi.nlm.nih.gov/pubmed/25477382>`__

-  `In silico pooling of ChIP-seq control experiments. Sun G, Srinivasan
   R, Lopez-Anido C, Hung HA, Svaren J, Keleş S. PLoS One. 2014 Nov
   7;9(11):e109691. doi: 10.1371/journal.pone.0109691. eCollection 2014.
   PMID: 25380244 <http://www.ncbi.nlm.nih.gov/pubmed/25380244>`__

-  `A comparison of control samples for ChIP-seq of histone
   modifications. Flensburg C, Kinkel SA, Keniry A, Blewitt ME, Oshlack
   A. Front Genet. 2014 Sep 25;5:329. doi: 10.3389/fgene.2014.00329.
   eCollection 2014. PMID:
   25309581 <http://www.ncbi.nlm.nih.gov/pubmed/25309581>`__

-  `ChIP-Enrich: gene set enrichment testing for ChIP-seq data. Welch
   RP, Lee C, Imbriano PM, Patil S, Weymouth TE, Smith RA, Scott LJ,
   Sartor MA. Nucleic Acids Res. 2014 Jul;42(13):e105. doi:
   10.1093/nar/gku463. Epub 2014 May 30. PMID:
   24878920 <http://www.ncbi.nlm.nih.gov/pubmed/24878920>`__

    Emphasizes adjusting for gene locus length and that two commonly
    used gene set enrichment methods, Fisher's exact test and the
    binomial test implemented in Genomic Regions Enrichment of
    Annotations Tool (GREAT), can have highly inflated type I error
    rates and biases in ranking.

Bias issues
~~~~~~~~~~~

-  `Proc Natl Acad Sci U S A. 2013 Nov 12;110(46):18602-7. doi:
   10.1073/pnas.1316064110. Epub 2013 Oct 30. Highly expressed loci are
   vulnerable to misleading ChIP localization of multiple unrelated
   proteins. Teytelman L1, Thurtle DM, Rine J, van Oudenaarden
   A. <http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3831989/>`__

    We analyzed ChIP-Seq peaks of the Sir2, Sir3, and Sir4 silencing
    proteins and discovered 238 unexpected euchromatic loci that
    exhibited enrichment of all three. Surprisingly, published ChIP-Seq
    datasets for the Ste12 transcription factor and the centromeric Cse4
    protein indicated that these proteins were also enriched in the same
    euchromatic regions with the high Sir protein levels. The 238 loci,
    termed ”hyper-ChIPable“, were in highly expressed regions with
    strong polymerase II and polymerase III enrichment signals, and the
    correlation between transcription level and ChIP enrichment was not
    limited to these 238 loci but extended genome-wide. ... Whereas ChIP
    is a broadly valuable technique, some published conclusions based
    upon ChIP procedures may merit reevaluation in light of these
    findings.

-  `Insightful post on PubPeer related to
   this <https://pubpeer.com/publications/591EB69E4EA0D85E6C76D2D9CACC1D>`__

    Oh, also, if you are not aware of it, Vishy Iyer's recent PLOS One
    paper finds the exact same artifact as we do.
    http://www.plosone.org/article/authors/info%3Adoi%2F10.1371%2Fjournal.pone.0083506;jsessionid=F590D75E9C265BA38D012211B9B97E33
    And related to this discussion:
    http://www.biomedcentral.com/1471-2164/11/414
    http://www.biomedcentral.com/1471-2164/14/254/abstrac
    http://www.biomedcentral.com/1471-2164/14/638 And this paper from
    Kevin Struhl:
    http://www.plosone.org/article/related/info%3Adoi%2F10.1371%2Fjournal.pone.0005029;jsessionid=93B6A4A5F2062E6B1F15E8997133060D

    Below are other publications reporting the expression-associated
    ChIP artifact. Fan X, 2009 "Where Does Mediator Bind In Vivo?" (Work
    in S. cerevisiae questioning reports of pervasive genome-wide
    binding of the Mediator complex.) Waldminghaus T, 2010 "ChIP on
    Chip: surprising results are often artifacts" (Work in E. coli; also
    see arising correspondence Schindler D, 2013.) Park D, 2013
    "Widespread Misinterpretable ChIP-seq Bias in Yeast" (Analysis very
    similar to ours.) Kasinathan S, 2014 "High-resolution mapping of
    transcription factor binding sites on native chromatin" (Questions
    specificity of standard ChIP in S. cerevisiae and at HOT regions of
    Drosophila. This work possibly provides a solution to the artifact
    with a modification of the ChIP technique.)
    http://www.ncbi.nlm.nih.gov/pubmed/24173036#cm24173036\_3919

-  `Widespread misinterpretable ChIP-seq bias in yeast. Park D, Lee Y,
   Bhupindersingh G, Iyer VR. PLoS One. 2013 Dec 9;8(12):e83506. doi:
   10.1371/journal.pone.0083506. eCollection 2013. PMID:
   24349523 <http://www.ncbi.nlm.nih.gov/pubmed/24173036#cm24173036_3919>`__

-  `Fan X and Struhl, 2009 "Where Does Mediator Bind In Vivo?" PLOS One.
   Published: April 03, 2009DOI:
   10.1371/journal.pone.0005029 <http://www.plosone.org/article/related/info%3Adoi%2F10.1371%2Fjournal.pone.0005029>`__

-  `Waldminghaus and Skarstad, 2010 "ChIP on Chip: surprising results
   are often artifacts" BMC Genomics. 2010 Jul 5;11:414. doi:
   10.1186/1471-2164-11-414. <http://www.ncbi.nlm.nih.gov/pubmed/20602746>`__

-  `Non-canonical protein-DNA interactions identified by ChIP are not
   artifacts. Bonocora RP, Fitzgerald DM, Stringer AM, Wade JT. BMC
   Genomics. 2013 Apr 15;14:254. doi:
   10.1186/1471-2164-14-254. <http://www.ncbi.nlm.nih.gov/pubmed/23586855>`__
   (Concerns the E. coli data.)

-  `High-resolution mapping of transcription factor binding sites on
   native chromatin. Sivakanthan Kasinathan,Guillermo A Orsi, Gabriel E
   Zentner, Kami Ahmad & Steven Henikoff. Nature Methods 11, 203–209
   (2014)
   doi:10.1038/nmeth.2766 <http://www.nature.com/nmeth/journal/v11/n2/full/nmeth.2766.html>`__

    The resulting occupied regions of genomes from affinity-purified
    naturally isolated chromatin (ORGANIC) profiles of Saccharomyces
    cerevisiae Abf1 and Reb1 provide high-resolution maps that are
    accurate, as defined by the presence of known TF consensus motifs in
    identified binding sites, that are not biased toward accessible
    chromatin and that do not require input normalization.

Related
~~~~~~~

-  ChIA- PET - `Genome-wide map of regulatory interactions in the human
   genome. Heidari N, Phanstiel DH, He C, Grubert F, Jahanbani F,
   Kasowski M, Zhang MQ, Snyder MP. Genome Res. 2014 Dec;24(12):1905-17.
   doi: 10.1101/gr.176586.114. Epub 2014 Sep 16. PMID:
   25228660 <http://www.ncbi.nlm.nih.gov/pubmed/25228660>`__

Motif identification
~~~~~~~~~~~~~~~~~~~~

-  `Cis-regulatory Element Annotation
   System <http://liulab.dfci.harvard.edu/CEAS/>`__ by Hyunjin Shin and
   Tao Liu from Xiaole Shirley Liu's Lab

    A tool designed to characterize genome-wide protein-DNA interaction
    patterns from ChIP-chip and ChIP-Seq of both sharp and broad binding
    factors. As a stand-alone extension of our web application CEAS
    (Cis-regulatory Element Annotation System), it provides statistics
    on ChIP enrichment at important genome features such as specific
    chromosome, promoters, gene bodies, or exons, and infers genes most
    likely to be regulated by a binding factor. CEAS also enables
    biologists to visualize the average ChIP enrichment signals over
    specific genomic features, allowing continuous and broad ChIP
    enrichment to be perceived which might be too subtle to detect from
    ChIP peaks alone.

-  `ab initio motif finder
   MEME <http://www.ncbi.nlm.nih.gov/pubmed/16845028>`__ and the related
   `MEME suite <http://www.ncbi.nlm.nih.gov/pubmed/19458158>`__

-  `MEME-LaB wraps the popular ab initio motif finder in a web
   tool <http://www.ncbi.nlm.nih.gov/pubmed/23681125>`__

-  `Motif enrichment tool. Blatti C, Sinha S. Nucleic Acids Res. 2014
   Jul;42(Web Server issue):W20-5. doi: 10.1093/nar/gku456. Epub 2014
   May 23. PMID:
   24860165 <http://www.ncbi.nlm.nih.gov/pubmed/24860165>`__

-  `Motif-based analysis of large nucleotide data sets using
   MEME-ChIP <http://www.ncbi.nlm.nih.gov/pubmed/24853928>`__
