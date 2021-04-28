# CoNLL
This project is from my Master Thesis. 
We are going to see **4 out-of-the-box tools** available
completely free of charge using the Python language. These are **NLP** libraries
that provide the possibility of doing **Name Entity Recognition (NER)** .  

The dataset on which
we trained the models is **CoNLL-2003** from the Conference on Computational
Natural Language Learning.
The four NLP techniques used to create this tool are increasingly popular in
the modern landscape:
* **Flair** is a powerful
NLP (Natural Language Processing) library, open-sourced and developed by
Zalando Research; 
* **SpaCy** is also an open-sourced library and free for advanced
NLP in Python. SpaCy is designed for production use in applications that have
to process big volumes of texts. 
* Then we will use the **Conditional Random
Fields**, a class of discriminative models to prediction tasks where contextual
information are used in the prediction. We will train a CRF model for named entity
recognition using sklearn-crfsuite. 
* To conclude, the last used tool we make
available is **BERT**, Bidirectional Encoder Representations from Transformers,
a new language representation model created by Google. BERT is created to
pretrain deep bidirectional model with unlabeled text by conditioning on both
left and right context in all layers.

The shared task of CoNLL-2003 concerns language-independent named
entity recognition.   
The structure of the training and test data is concentrated to
have four types of named entities: **persons, locations, organizations and names
of miscellaneous entities** not belonging to the previous groups. 
