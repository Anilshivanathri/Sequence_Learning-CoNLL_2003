## Sequence_Learning-CoNLL_2003

### Statement
Using  CoNLL2003  data,  predict  tagged  NER  using  CRF  Algorithm.  Also,  tune  the  algorithm  and  explore  the learnings that have been done by the CRF Model.
### Dataset
The CoNLL-2003 shared task data files contain four columns separated by a single space. Each word has been put on a separate line, and there is an empty line after each sentence. The first item on each line is a word, the second a part-of-speech (POS) tag, the third a syntactic chunk tag, and the fourth the named entity tag. The  chunk  tags  and  the  named  entity  tags  have the  format  I-TYPE,  which  means  that  the  word  is  inside  a phrase of type TYPE. Only if two phrases of the same type immediately follow each other, the first word of the second  phrase  will  have  tag  B-TYPE  to  show  that  it  starts a new phrase. A  word  with  tag  O  is  not  part  of  a phrase.
