Text analysis of all 163 000+ theoretical high energy physics papers on arXiv (with hep-th as primary or cross-list category), from 1986 to 2023. 

Exploration of the following possible tasks: 1) counting; 2) feature extraction; 3) classification; 4) question answering; 5) summarising; 6) recommending papers / research directions. The results are the following: 

1) interesting temporal trends appear in title words popularity;

<img width="1021" alt="title words shares" src="https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/1aac5930-0f9f-4d2b-8a33-af186e5ffd07">
 
2) 2-words combinations of title words turn out to correspond to hep-th concepts and allow effective feature extraction and CONCEPT embedding of abstracts;
 
3) classifiers of article categories are built as Neural Networks (NNs) based on either CONCEPT or SciBERT embedding;

<img width="493" alt="confusion matrix proper" src="https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/bbaadccc-628e-4723-b2b4-fe939f398d08">

4) through a more sophisticated NN, the CONCEPT classifier works also for the subcategories within hep-th category;
  
<img width="495" alt="confusion matrix" src="https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/90d5d296-a4cb-4ae9-81bc-cde0f7739051">
 
5) effective question answering and summarization of article introductions, through high level AI WL functionality;
 
6) a first basic recommendation algorithm, according to distance in feature space.
 
In perspective it looks sensible to relate papers in feature space and thus inspire new discoveries.


![graph papers concept space](https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/8657f3fa-47ac-4ec9-adf2-2a33042a009a)


All this can be found in the notebook named arXivDataAnalysisV1.3 (to unzip).

Then, as a partial aside, in the notebook Affiliation Countries, we also show the computation of total number of papers over affiliated co-authors, for each country in 2023. This is done using directly inspirehep API. The results are the following:

<img width="733" alt="hep-th world ranking full" src="https://github.com/Daniele-Gregori/ArXiv-Hepth-Data-Analysis/assets/147420933/3ba23da7-ae0f-4988-a4bf-e0acf75655cf">

