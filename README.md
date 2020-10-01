# stanford-coreNLP
This is python implementation of stanford coreNLP on bulk data

1) Install CoreNLP
wget https://nlp.stanford.edu/software/stanford-corenlp-full-2018-10-05.zip https://nlp.stanford.edu/software/stanford-english-corenlp-2018-10-05-models.jar

2) unzip stanford-corenlp-full-2018-10-05.zip
3) mv stanford-english-corenlp-2018-10-05-models.jar stanford-corenlp-full-2018-10-05

Once installed just follow following steps on jupyter notebook terminal:
1) cd stanford-corenlp-full-2018-10-05
2) java -mx6g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -timeout 5000

References
1) If showing error please follows steps in this article:
https://towardsdatascience.com/natural-language-processing-using-stanfords-corenlp-d9e64c1e1024 

2)https://github.com/yaowser/yelp-initial/blob/feb5d289845905b782ee5709dae3e9f6e001ccce/yelp_updated_20180502/.ipynb_checkpoints/text2sentiment1-checkpoint.ipynb
