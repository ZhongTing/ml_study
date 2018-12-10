# 簡單的語音辨識
ML Study Group Lab 語音辨識練習
## setup
1. 到[這裡](https://github.com/manashmndl/DeadSimpleSpeechRecognizer/tree/master/data)下載data放到simple_speech_recognition/data/
2. 執行 preprocess.py 建立bed.npy, cat.npy, happy.npy
3. 執行automatic_speech_recognition.ipynb

## note
* DeadSimpleSpeechRecognition.ipynb是原作者的筆記
* 在前處理已經針對已經wav取mfcc vector了

## ref
1. [之前做的聲音特徵擷取survey](https://docs.google.com/presentation/d/1FVffBsj6gPA6VGPw2G6htqPU02_IPZaSUGBLWOv46tg/edit#slide=id.p)
2. [自動語音識別(Automatic Speech Recognition) -- 觀念與實踐](https://ithelp.ithome.com.tw/articles/10195763)
3. [Building a Dead Simple Speech Recognition Engine using ConvNet in Keras](https://blog.manash.me/building-a-dead-simple-word-recognition-engine-using-convnet-in-keras-25e72c19c12b)
4. [原作者 source code](https://github.com/manashmndl/DeadSimpleSpeechRecognizer)