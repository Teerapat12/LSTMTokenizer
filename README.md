# LSTMTokenizer

This is an attempt to use Deep Learning (LSTM) to predict where to cut a Thai word given a Thai String.

For example, suppose "ไก่จิกเด็กตายบนปากโอ่ง" was given, the tokenizer should seperate the string into "ไก่|จิก|เด็ก|ตาย|บน|ปาก|โอ่ง"


Result (On similar source but seperated into training and testing set
Test set 1
Start comparing
Accuracy : 96.76
Precision : 90.18
Recall : 94.02
F1 Score : 92.06
Test set 2
Start comparing
Accuracy : 96.51
Precision : 90.35
Recall : 92.61
F1 Score : 91.47
Test set 3
Start comparing
Accuracy : 96.50
Precision : 90.79
Recall : 92.27
F1 Score : 91.52
