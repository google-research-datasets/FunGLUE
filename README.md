# FunGLUE

FunGLUE is a Natural Language Benchmark containing native language (Hindi, Bengali, Tamil) inspired misspellings in a second language (English).
Language asymmetries on the web forces people to use languages they have no formal education in.
While people are familiar with words in such a second language, they are often unfamiliar with spellings.
In an attempt to phonetically spell such words, we also see an influence of their native languages.
Absence of certain phonemes, or overloading to the same grapheme in the native language results in phonetic confusions when speaking words in a second language.
This phonetic confusion also shows up in misspellings.

FunGLUE contains such L1 inspired misspellings in L2 for 7 tasks in the <a href=”https://super.gluebenchmark.com/”>SuperGLUE benchmark</a>.

More details about how the dataset is created can be found in our paper <a href="https://aclanthology.org/2023.acl-long.145/">Bi-Phone: Modeling Inter Language Phonetic Influences in Text</a>.

# Cite 

If you find this data useful in your research please cite the following paper:
```
@inproceedings{gupta-etal-2023-bi,
    title = "Bi-Phone: Modeling Inter Language Phonetic Influences in Text",
    author = "Gupta, Abhirut  and
      Sai, Ananya B.  and
      Sproat, Richard  and
      Vasilevski, Yuri  and
      Ren, James  and
      Jash, Ambarish  and
      Sodhi, Sukhdeep  and
      Raghuveer, Aravindan",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.145",
    pages = "2580--2592",
    abstract = "A large number of people are forced to use the Web in a language they have low literacy in due to technology asymmetries. Written text in the second language (L2) from such users often contains a large number of errors that are influenced by their native language (L1).We propose a method to mine phoneme confusions (sounds in L2 that an L1 speaker is likely to conflate) for pairs of L1 and L2.These confusions are then plugged into a generative model (Bi-Phone) for synthetically producing corrupted L2 text.Through human evaluations, we show that Bi-Phone generates plausible corruptions that differ across L1s and also have widespread coverage on the Web.We also corrupt the popular language understanding benchmark SuperGLUE with our technique (FunGLUE for Phonetically Noised GLUE) and show that SoTA language understating models perform poorly.We also introduce a new phoneme prediction pre-training task which helps byte models to recover performance close to SuperGLUE. Finally, we also release the SuperGLUE benchmark to promote further research in phonetically robust language models. To the best of our knowledge, FunGLUE is the first benchmark to introduce L1-L2 interactions in text.",
}
```
