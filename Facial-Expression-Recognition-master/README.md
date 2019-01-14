

Opensource deep learning framework [TensorFlow](https://www.tensorflow.org) is used in **Facial Expression Recognition(FER)**. 
The trained models achieved 65% accuracy in fer2013. If you like this, please give me a star.

#### Dependencies

FER requires:
- Python (>= 3.3)
- TensorFlow (>= 1.1.0) [Installation](https://www.tensorflow.org/install/)
- OpenCV (python3-version) [Installation](http://docs.opencv.org/master/da/df6/tutorial_py_table_of_contents_setup.html)



#### Usage
###### demo
To run the demo, just type:
```shell
python3 main.py
```
Then the program will create a window to display the scene capture by webcamera. You need press <kbd>SPACE</kbd> key to capture face in current frame and recognize the facial expression.

If you just want to run this demo instead of training the model from scratch, the following content can be skipped.

###### train models
If you want to train a model from scratch by yourself, download the fer2013 datasets in [kaggle(91.97MB)](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). Then extract the data to `data/fer2013` folder.

It's is import that modifying the `MODE`(in `main.py`) from `demo` to `train`  before you start training.
Then type:
```shell
python3 main.py
```

