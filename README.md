# NER
&emsp;&emsp; This is the implemention of  named entity recogntion model.  It includes lstm, lstm+char, lstm+crf, lstm+char+crf, cnn, cnn+char, cnn+crf, cnn+char+crf.  It shows the influence of character embedding and CRF. And it also shows the performance of LSTM and CNN as feature extractors respectively. The following table shows the experimental results of different models on CoNLL2003 dataset. 

Model|F1|
--|:--:   
LSTM|88.30  
LSTM+char|   
LSTM+CRF|89.59
LSTM+char+CRF|90.86   
CNN|87.95   
CNN+char|   
CNN+CRF|88.22   
CNN+char+CRF|90.22    
#requirements  
* pytorch 1.0  
* tensorboardX  


## reference
* https://github.com/jiesutd/NCRFpp
