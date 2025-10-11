
The journey from **lexical search** to **semantic search** to a more advanced **hybrid search** is about how information retrieval can be improved.

Lexical to semantic search: https://ranjas.substack.com/p/vector-database

The lexical (keyword) search results are scored by similarity methods like TF-IDF whose scales are usually unbounded, while the semantic or vector search results are scored by distance methods like cosine similarity etc. 
whose scales are within a closed interval. Hybrid search is sort of a ‘sum’ of lexical search and semantic search and when done right, can yield more relevant results than either of those parts. 


The methods used to merge the lexical and semantic search results to get to a hybrid search query have been well explained in the article by Elastic Search service.
📌https://www.elastic.co/search-labs/blog/hybrid-search-elasticsearch

