# Summary

The Hungarian CoBaLD dataset is derived from [UD Hungarian Szeged](https://github.com/UniversalDependencies/UD_Hungarian-Szeged), which in turn is derived from the Szeged Dependency Treebank (Vincze et al. 2010). It consists of the first 300 sentences from the UD Hungarian Szeged training set and it's size is 7,165 tokens.

# Introduction 

In order to create this dataset, we took the first 300 sentences from the UD Hungarian Szeged training set and annotated them with the help of our DL-based parser trained on CoBaLD Rus with the use of XLM-RoBERTa Large encoders, then professional linguists manually checked the annotation. The initial quality of the parser for DS is 90.8%, SC - 93.6%. The percent of manual corrections is 11.6% for DS and 14.6% for SC. 
