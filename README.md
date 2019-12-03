# IBGEC
Code and Data release for the papre Inherent Biases in Grammatical Error Correction and Text Simplification
The unseenest github repo deals with a comfortable implementation in python 3 for unseenest algorithm to predict the histogram of a discreet probabillity while sampling from only some of the discreet possible values.

The poissonBinomial github repo deals with implementations of papers to efficiently and comfortably calculate Poisson Binomial CDF PDF etc.

The batches contains 2,500 simplification and grammatical error correction tasks done by humans (mostly 50 examples per sentence, more on that in the paper).
The batches directory also contains the data of validation by humans of grammatical error corrections done by humans (from the data above).

Please cite this paper if you find our resources useful

bib (from ACL anthology):

@inproceedings{choshen-abend-2018-inherent,
    title = "Inherent Biases in Reference-based Evaluation for Grammatical Error Correction",
    author = "Choshen, Leshem  and
      Abend, Omri",
    booktitle = "Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2018",
    address = "Melbourne, Australia",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P18-1059",
    doi = "10.18653/v1/P18-1059",
    pages = "632--642",
    abstract = "The prevalent use of too few references for evaluating text-to-text generation is known to bias estimates of their quality (henceforth, low coverage bias or LCB). This paper shows that overcoming LCB in Grammatical Error Correction (GEC) evaluation cannot be attained by re-scaling or by increasing the number of references in any feasible range, contrary to previous suggestions. This is due to the long-tailed distribution of valid corrections for a sentence. Concretely, we show that LCB incentivizes GEC systems to avoid correcting even when they can generate a valid correction. Consequently, existing systems obtain comparable or superior performance compared to humans, by making few but targeted changes to the input. Similar effects on Text Simplification further support our claims.",
}
