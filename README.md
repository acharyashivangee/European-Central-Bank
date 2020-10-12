# European-Central-Bank

The European Central Bank is the central bank of the Eurozone, a monetary union of 19 EU member states which employ the euro. The ECB releases various documents to better communicate policy to the markets and the public. The ECB publishes a wide range of regular and ad hoc reports and research papers. These publications offer a deeper insight into the ECB’s activities and explain the background to some of its decisions. 
In this project, we make a scrapper designed to extract ECB documents related to Monetary Policy (accessible at https://www.ecb.europa.eu/pub/pub/mopo/html/index.en.html), which acts as our dataset. 

Thereafter, we apply various topic models to draw out a comprehensive analysis of the various topics accumulated from 1999-2020. We also draw out a comparisional analysis of the various models by checking:
1. Its wordclouds and words relevant to monetary policy.
2. Coherence scores and Perplexity scores of each model.
3. Finding the optimal number of topics corresponding to the coherence scores.


References:
1. Paper by David M. Blei, Andrew Y. Ng, and Michael I. Jordan on LDA (https://ai.stanford.edu/~ang/papers/nips01-lda).
2. https://datascienceplus.com/evaluation-of-topic-modeling-topic-coherence/
3. https://medium.com/technovators/topic-modeling-art-of-storytelling-in-nlp-4dc83e96a987
4. http://qpleple.com/topic-coherence-to-evaluate-topic-models/
