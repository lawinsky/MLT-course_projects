# mlt
Completed course projects from Master in Language Technology at University of Gothenburg  
Author: Lawin Khalid



#### Artificial Intelligence: Cognitive Systems  
_Visual Question Answering on Balanced Binary Datasets_

This paper presents visual question answering
experiments on binary datasets
with different characteristics with regard
to degree of balance and image type. We
address the importance of a truly balanced
dataset by making use of a semi-balanced
dataset with clipart scenes, an unbalanced
subset of real images, and a truly balanced
subset of real images. Since a pretrained
model, trained on real images, is used for
representation of image features, this selection
of datasets also examines how well
these features applies to clipart images.
Moreover, we examine the datasets’ sensitivity
to excluding visual features, and
their sensitivity to altering the language
representation by using GloVe vectors in
some of the models. Findings highlight
the importance of a truly balanced dataset,
and shows that features from a pretrained
model can also be exploited for use on
clipart images. We also show that training
on truly balanced data can improve the
performance, likely because it forces the
model to exploit visual features more efficiently.



#### Dialogue Systems 2
_Movie Search App_

This report will present and discuss the implementation procedure of the course project,
including pointing out some issues that was encountered during building the application. The
purpose of this project was to build a movie search app, capable of finding various information
about movies and report this information to the user. The aim was to implement a natural dialogue
flow, and to explore the capabilities of the platform that was used for building the application.
The platform used was Talkamatic Dialogue Manager (TDM). To get the information for the
queries, the API Open Movie Database was used.



#### Language Technology Resources
_Word2Vec study on the new KubHist corpus_

This study presents neural word embedding
experiments on a new version of
the Swedish historical newspaper corpus,
KubHist. We investigate whether the new,
extended corpus can overcome some issues
that the older version suffered from
when used withWord2Vec. Findings show
a similar behaviour on the new version as
on the old version of the corpus, when
used with Word2Vec. However, the larger
size, together with our approach, solves
some of the issues, but instead amplifies
issues regarding OCR errors in the vectors.
