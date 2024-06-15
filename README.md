# Summary

The Hungarian CoBaLD dataset is derived from [UD Hungarian Szeged](https://github.com/UniversalDependencies/UD_Hungarian-Szeged), which in turn is derived from the Szeged Dependency Treebank (Vincze et al. 2010). It consists of the first 300 sentences from the UD Hungarian Szeged training set and it's size is 7,165 tokens.

# Introduction 

To create the dataset, we took the first 300 sentences from the UD Hungarian Szeged training set and annotated them with the help of our DL-based parser trained on CoBaLD Rus with the use of XLM-RoBERTa Large encoders. After it, the annotation was manually checked by professional linguists. The initial quality of the parser was 90.8% for semantic (deep) relations (DSs), and 93.6% - for semantic classes (SCs) in Russian. The percent of manual corrections for Hungarian annotation turned out to be 11.6% for DS and 14.6% for SC. 
