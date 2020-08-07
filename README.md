# Music-Genre-Classification
A python machine learning project done under intership of "Indian Servers" Company.
The project is to classify a music genre from 10 categories using LSTM Neural Network.

Project Members -- :
Bharat Dave  -- 
Vinayak Chavan -- 
Ajaykumar Gupta  --
Rutvik Bhalekar

Project Done Under Internship of Indian Servers Group 191 Batch 11


-> Music Genre Classification with LSTMs
   
 * Classify music files based on genre from the GTZAN music dataset.
 * GTZAN corpus is included for easy of use
 * Use multiple layers of LSTM Recurrent Neural Nets
 * Implementations in Keras.

->Test trained LSTM model
 In the `./weights/` you can find trained model weights and model architecture.

 To test the model on your custom audio file, run

     python predict_example.py path/to/custom/file.mp3
 or to test the model on our custom files, run

     python predict_example.py audio/classical_music.mp3

-> Audio features extracted
 * [MFCC](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum)
 * [Spectral Centroid](https://en.wikipedia.org/wiki/Spectral_centroid)
 * [Chroma](http://labrosa.ee.columbia.edu/matlab/chroma-ansyn/)
 * [Spectral Contrast](http://ieeexplore.ieee.org/document/1035731/)

-> Dependencies
 * [Python3](https://www.anaconda.com/distribution/#download-section)
 * [numpy](https://numpy.org)
 * [librosa](https://librosa.github.io/librosa):  For audio feature extraction
 * [Keras](https://keras.io)
 * [PyTorch](http://pytorch.org)
    

