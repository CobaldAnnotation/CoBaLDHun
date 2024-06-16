# General information

The Hungarian CoBaLD dataset is derived from [UD Hungarian Szeged](https://github.com/UniversalDependencies/UD_Hungarian-Szeged), which in turn is derived from the Szeged Dependency Treebank (Vincze et al. 2010). It consists of the first 300 sentences from the UD Hungarian Szeged training set. It includes news texts, and its size is 7,165 tokens.

To create the dataset, we annotated the sentences with the help of our DL-based parser trained on CoBaLD Rus with the use of XLM-RoBERTa Large encoders. After it, the annotation was manually checked by professional linguists. The initial quality of the parser was 90.8% for semantic (deep) relations (DSs), and 93.6% - for semantic classes (SCs) for Russian texts. The percent of manual corrections for Hungarian annotation turned out to be 11.6% for DSs and 14.6% for SCs. 

# Annotation comments

As in other CoBaLD datasets, most tokens here are provided with both - a SC and a DS. The exceptions are grammatical and idiomatical units. The former possess the semantical classes only as they do not express deep semantic relations. For the latter, a SC and a DS are given for the core token of the idiom only, while the dependent elements have blanks both in the columns for the SCs and for the DSs.

There also should be made several comments concerning Hungarian.

There are postpositons instead of prepositions here - as functionally they behave as presositions, we attributed them to the SC PREPOSITION in the dataset.

Besides, there are adjectives derived from the postpositions, as in the example:

diploma nelkül  = without diploma ('nelkül' is the postposition)
diploma nelküli orvos  =  a doctor without diploma ('nelküli' is an adjective derived from the postposition).
   
Such adjectives are also attributed to the SC PREPOSITION.
