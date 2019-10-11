# hackindore2_Archers
Book recommendation system working on content based recommendation

1.We used the concept of vectorizer,which provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words,we can also encode new documents using that vocabulary. 

2.Tfid vectorizer is an acronym than stands for “Term Frequency – Inverse Document” Frequency which are the components of the resulting scores assigned to each word. Term Frequency: This summarizes how often a given word appears within a document.
In our book recommendation system the Tfid Vectorizer is reducing the overall weightage of each component,thus reducing the load of calculation.

3.Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.
The cosine of two non-zero vectors can be derived by using the Euclidean dot product formula:

A.B= |A||B|cos(theta)
