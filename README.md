# ArXiv-Data-Analysis-V1
First version of the analysis of 43000 theoretical physics papers in the "hep-th" category of arXiv from 2017/7 to 2023/9. In particular here the words of all article titles are counted, sorted and visually represented through a wordcloud video.

Full post text:

How to summarise 6 years of theoretical high energy physics…

Since when I started doing research with my master thesis in 2017, I wrote rather few papers. However it turns out that during these 6 years the global community of theoretical physicists produced over 40,000 papers! 

More precisely, I downloaded (through API) the data of 43,000 papers in the “hep-th” category of #arxiv . This is actually only one particular subfield of theoretical physics, #hepth short for “High Energy Physics - Theory”.

This is a huge mass of very difficult data to analyse. We theoretical physicists ourselves can usually understand well only a minor part of these papers. In fact it would be nearly impossible to read all their main texts. Moreover for a full understanding, also all the mathematical calculations should be at least partially reproduced.

It is interesting to think about how #programs and AI could help giving physicists precious insight in this horrific mess!
A very first basic step I made is to collect all the titles of the articles and count their words. The results are the following.

1. In the first video it is shown a “wordcloud” of the most frequent words for each month from July 2017 to September 2023.
2. In the second table it is shown the total count of the 20 most frequent words.
   
It turns out that the most popular word is “quantum” (1st) and it is often associated with “gravity” (4th) or “field” (5th). It is followed just below by  “black” (2nd), often associated with “holes” (7th) or “hole” (10th). 

Besides the obvious “theory”/“theories”/“model” (3rd, 6th, 8th), down below we find the strange letter “n” (9th), which seems to stand for some integer number indicating a particular “gauge” (11th) theory. Notice the full name of this should have been “supersymmetric” gauge theory (n indicating the amount of supersymmetry, or a particular limit) but the first word is absent… as also absent is the “Higgs” or “God’s” particle, for some controversial reason...

Other noticeable words are “holographic” (12th), “symmetry” (16th), “entanglement” (17th), “string” (19th) and “dark” (20th).

Data analysis realised with #wolframlanguage . Any suggestion for further investigations is welcome!
