# topic-modeling

Topic model aims to extract topics from large-scale unstructured corpora. The theme is the core idea expressed by corpus. From a statistical point of view, word frequency distribution is used to depict the theme. A sentence, a paragraph, and a document are considered to be generated from a topic-and word-based probability model. In the field of topic model, the most commonly used algorithm is LDA (Latent Dirichlet Allocation). Specifically, LDA is an unsupervised machine learning technology. It treats the nature of the document as a collection of potential topics, and each topic is based on word distribution. LDA uses the BoW (Bag of Words) method to transform each document to word frequency vector, thus transforming unstructured data into easy-to-model numerical information. 

In the workflow, it reads textual data from a table and converts them into documents. The documents are then preprocessed, i.e. tagged, filtered, lemmatized, etc. After that, the Topic Extractor node can be applied to the preprocessed documents. However, the node requires users to input the number of topics that should be extracted beforehand. After pre-processing, the Topic Extractor node can be executed and a tag cloud is created to visualize the topics' terms.

![YuruLi](https://github.com/YuruLiForPhDApplication/topic-modeling/blob/master/topic%20model.png)

