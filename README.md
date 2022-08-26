# SUS_URL
- Identifying potential malicious URLS using Python &amp; ML Techniques
- Here we Static analysis of Lexical features to extract url string elememts which may be potentially harmful.
- The dataset used is from kaggle <https://www.kaggle.com/datasets/siddharthkumar25/malicious-and-benign-urls>
- The Accuracy proved to be 99.6% which is very good compared to Existing methods of Static analysis
- We built classifiers using Logistic regression,Random forest and XGBOOST
- We've also applied this to identify javascript Obfuscation in URLs which is quite Common these days
- URL shortening is a major problem to classfiers to which we've formulated an approach using regular expressions and url decoders to detect potentially harmful sites.
