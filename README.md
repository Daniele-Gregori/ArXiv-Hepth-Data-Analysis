Text analysis of all 163 000+ theoretical high energy physics papers on arXiv (with hep-th as primary or cross-list category), from 1986 to 2023. Exploration of the following possible tasks: 1) counting; 2) feature extraction; 3) classification; 4) question answering; 5) summarising; 6) recommending papers / research directions.
The results are the following: 
	1) interesting temporal trends appear in title words popularity;
	2) 2-words combinations of title words turn out to correspond to hep-th concepts and allow effective feature extraction and 	CONCEPT embedding of abstracts;
	3) classifiers of article categories are built as Neural Networks (NNs) based on either CONCEPT or SciBERT embedding;
	4) through a more sophisticated NN, the CONCEPT classifier works also for the subcategories within hep-th category;
	5) effective question answering and summarization of article introductions, through high level AI WL functionality;
	6) a first basic recommendation algorithm, according to distance in feature space.
In perspective it looks sensible to relate papers in feature space and thus inspire new discoveries.

<img width="1021" alt="title words shares" src="https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/1aac5930-0f9f-4d2b-8a33-af186e5ffd07">

![graph papers concept space](https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/8657f3fa-47ac-4ec9-adf2-2a33042a009a)
