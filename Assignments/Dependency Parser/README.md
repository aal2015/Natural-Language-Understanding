# Paper Summary

**Name of the paper:** A Fast and Accurate Dependency Parser using Neural Networks'
<br />
**Link:** https://aclanthology.org/D14-1082.pdf
<br />
 This paper seeks to solve issues current parsers have due to basing its classification on millions of sparse indicators featured. Three identified issues are: (1) poor feature generalization, (2) restricted parsing speed due to the feature extraction step, and (3) the level of incompleteness among the features. To solve this, the authors of the paper propose to use dense representation/embedding of words and use it with part-of-speech (POS), and dependency labels to train a neural network model for the greedy, transition-based parser. In the result, authors found the studied parser to display superior accuracy and speed than other parsers based on sparse indicator features.
