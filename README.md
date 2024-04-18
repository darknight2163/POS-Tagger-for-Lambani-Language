# POS-Tagger-for-Lambani-Language
Develop a custom Part-of-Speech (POS) tagger for the Lambani corpus, which includes sentences demarcated by &lt;START> and &lt;END> tokens. The tagger must assign tags to words, including untagged ones, with using Hidden Markov Model (HMM) and Viterbi decoding.
## Dataset
Here, lambani.csv is the original labeled dataset with POS tags, and lambani_preprocessed.csv is the modified one then lambani_training.txt is the training data with lambani_testing.txt is the test data. One can prepare the same format for testing and training data for low-resource Indian languages. (NB: Keep the data in .txt format not in csv). Then, proceed for training
## Training and Testing
Use the LAMBANI_POSTagger_200020044.ipynb file for training and testing. You can individually use precision, recall, and F1-score for each POS tag, such as noun, verb, adjective, etc. 

Good Luck! 
