# ExtendableBookRecommendationSys
An extendable pipeline using NLP built to recommend items which have a description attached to it. 

Database is self curated and self scraped based on our custom needs.

We use sbert transformer to recommend books based on description. 2 methods are tested - A normal description encoded and the modified description encoding where we provide information that would help the transformer understand (By increasing the context provided as input).

The pipeline used for book recommendation can be extended to recommending research papers as well. This is shown in research-paper.ipynb file. 
