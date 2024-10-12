# Music-Genre-Classification

A python machine learning project done under intership of "Indian Servers" Company.
The project is to classify a music genre from 10 categories using LSTM Neural Network.

Hello! This is a python machine learning project done as part of internship. This machine learning model is created in **Python** and **LSTM Neural Network** and allows a user to upload an audio file, upon which the model classifies it into a music genre from the 10 categories

> **Note:** This is a project created as part of internship under the **Indian Servers** Company. 

# Audio Features Extracted

| Audio Features Extracted                    | Description                                                                | References                                           |
|---------------------------------------------|----------------------------------------------------------------------------|------------------------------------------------------|
| MFCC (Mel Frequency Cepstrum Coefficients)  | Describe overall shape of spectral envelope                                | https://en.wikipedia.org/wiki/Mel-frequency_cepstrum |
| Spectral Centroid                           | Indicates where the center of mass of spectrum is located                  | https://en.wikipedia.org/wiki/Spectral_centroid      |
| Spectral Contract                           | Measurment of energy differences between peaks and valleys in the spectrum | http://ieeexplore.ieee.org/document/1035731/         |
| Chroma                                      | Helps find the pitch of the audio                                          | http://labrosa.ee.columbia.edu/matlab/chroma-ansyn/  |

# Testing the LSTM Model
>**Note**:  In the `./weights/` you can find trained model weights and model architecture for reference.

 ## To test the model on your custom audio files
```bash
 python predict_example.py path/to/custom/file.mp3
```
 
 ## To test the model on our project files
```bash
 python predict_example.py audio/classical_music.mp3
```

# Members:
| Bharat Dave | Vinayak Chavan | Ajaykumar Gupta | Rutvik Bhalekar |
|-------------|----------------|-----------------|-----------------|





