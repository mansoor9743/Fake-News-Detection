# Natural Language Processing NLP
## Fake news Detection:
The proliferation of fake news in recent times has led to more focused research in computational tools able to identify reliable and trustworthy news. In this project we analyse and implement machine learning models for automatic fake news detection. Data consists of short statements of news releases, interviews, campaign speeches, Facebook posts and tweets made during the 2016 U.S presidential campaign from Politifact.com.. We use various pre-processing, vectorisation, parameter tuning methods across a range of classifiers to identufy fake news.
### Getting started: 
Download the 'Fake_news_detection.ipynb' Jupyter Notebook file and the data into a folder on your system. Unzip the contents of the data zip file. It consists of 3 TSV (tab separated) files. From terminal CD into the folder and launch Jupyter notebook. You can view the results of the code already run by me in the notebook in this repository. To rerun the code run 'restart and run all' from the notebook. The entire notebook will take approximately 80 minutes to execute.

### Prerequisites: 
Sklearn, NLTK and other libraries lumpy, pandas, seaborn etc needs to be installed if not already done.They are called in the initial line of the code. NLTK 'stopwords', NLTK('punkt'),NLTK ('maxent_treebank_pos_tagger') needs to be downloaded.
All the classifiers used are available when Sklearn is installed, except XGradientBoost Algorithm.
For installing XGradientBoost algorithm classifier please refer 'https://xgboost.readthedocs.io/en/latest/build.html'.
Note: A simple 'pip3 install xgboost' will install it most of the times. If not then please refer the above link.	

### License:
All the libraries and python code are open-source. The data has been made publicly available by the creator and hence does not need any license.

	
### Acknowledgements: 
William Wang for creating the LIAR dataset by collecting a decade long 12.8k manually labelled short statements from Politifact.com

### Dataset: 
Data that we use for this project is the 'LIAR' dataset, a public available fake news detection corpus. I have uploaded a zip file with the data. Download it to the folder having the 'fake_news_detection.ipynb' jupyter notebook. It contains 3 TSV files namely train.tsv, test.tsv and valid.csv.
The data can also be downloaded online from [LIAR Dataset](https://sites.cs.ucsb.edu/~william/data/liar_dataset.zip)

### References: 
* Wang, W. (2019). ”Liar, Liar Pants on Fire”: A New Benchmark Dataset for Fake News Detection. [online] arXiv.org. Available at: https://arxiv.org/abs/1705.00648
* Wang, W.Sites.cs.ucsb.edu.https://sites.cs.ucsb.edu/ william/papers/acl 2017. pdf
* Horne, B. and Adalı, S. (2017). This Just In: Fake News Packs a Lot in Title, Uses Simpler, Repetitive Content in Text Body, More Similar to Satire than Real News. [online] Arxiv.org. Available at: https://arxiv.org/pdf/1703.09398.
* Rubin, V. L. (2017). Deception Detection and Rumor Debunking for Social Media. In Sloan, L. & Quan-Haase, A. (Eds.) (2017) The SAGE Handbook of Social Media Research Methods, London: SAGE. https://uk.sagepub.com/en-gb/eur/the- sage-handbook-of-social-mediaresearch- methods/book245370
* Conroy, N.J., Rubin, V.L. and Chen, Y., 2015. Automatic deception detection: Meth- ods for finding fake news. Proceedings of the Association for Information Science and Technology, 52(1), pp.1-4
* Rashkin, H., Choi, E., Jang, J.Y., Volkova, S. and Choi, Y., 2017. Truth of varying shades: Analyzing language in fake news and politi- cal fact-checking. In Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (pp. 2931-2937)
* Shu, K., Sliva, A., Wang, S., Tang, J. and Liu, H., 2017. Fake news detection on socialmedia: A data mining perspective. ACM SIGKDD Explorations Newsletter, 19(1), pp.22-36
* Thorne, J. and Vlachos, A., 2018. Automated Fact Checking: Task Formulations, Methods and Future Directions. In Proceedings of the 27th International Conference on Computa- tional Linguistics (pp. 3346-3359)
* Long, Y., Lu, Q., Xiang, R., Li, M. and Huang, C. (2017). Fake News Detection Through Multi-Perspective Speaker Pro- files. [online] Aclweb.org. Available at: https://aclweb.org/anthology/I17-2043.
* Conroy, N., Chen, Y. and Rubin, V. (2015). Deception Detection for News: Three Types of Fakes. [online] Available at: https://onlinelibrary.wiley.com/doi/pdf/10. 1002 /pra2.2015.145052010083.
* Piccione, A. line] GitHub.(n.d.).[on- Available at:https://github.com/mikanikos/ADA Project/ blob /master/Data Analysis.ipynb.
* PolitiFact. (2019). Fact-checking U.S. pol- itics — PolitiFact. [online] Available at: (https://www.politifact.com/)
* Patel, n. (2019). nishitpatel01-Fake News Detection. [online] GitHub. Available at: https://github.com/nishitpatel01/Fake News Detection.
* Fotache, C. (2018). Text Classification in Python: Pipelines, NLP, NLTK, Tf-Idf, XG- Boost and more. [online] Medium. Available at: https://medium.com/@chrisfotache/text- classification-in-python-pipelines-nlp-nltk- tf-idf-xgboost-and-more-b83451a327e0.
* Bedi, G. (2018). Simple guide to Text Clas- sification(NLP) using SVM and Naive Bayes with Python. [online] Medium. Available at: https://medium.com/@bedigunjit/simple- guide-to-text-classification-nlp-using-svm- and-naive-bayes-with-python-421db3a72d34.

