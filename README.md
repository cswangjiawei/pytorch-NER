# NER
This is the implemention of  named entity recogntion model.  It includes lstm, lstm+char, lstm+crf, lstm+char+crf, cnn, cnn+char, cnn+crf, cnn+char+crf.  It shows the influence of character embedding and CRF. And it also shows the performance of LSTM and CNN as feature extractors respectively. The following table shows the experimental results of different models on CoNLL2003 dataset. 

Model|F1|
--|:--:   
lstm|88.30  
lstm+char|   
lstm+crf|89.59
lstm+char+crf|90.86   
cnn|87.95   
cnn+char|   
cnn+crf|88.22   
cnn+char+crf|90.22  

## reference
* https://github.com/jiesutd/NCRFpp
