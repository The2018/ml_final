# ml_final_project

Identifying the composer by listening to a piece of classical music is a task often associated with human knowledge of music. In music analysis, for a totally unfamiliar piece of music, we often try to identify the stylistic elements as well as historical context pertinent to the composer of that piece. In other words, we are asking people to recognize composers styles and it usually requires the combined knowledge of music theory and history.

This experiment tackles the previously mentioned task using machine learning methods. It focus on the automatic classification of classical music performances according to their composer. It achieves so by collecting audio data in MIDI and WAV form, extract features such as mel spectrogram or MFCC and then apply classification models (MLP, CNN, SVM, logistic regression). We compare their performance and test the model with unfamiliar piece of music.

## Required Files and Libraries
The following will be required for this project:
* The **`pretty_midi`** module for handling midi files, including extracting and modifying information.
* The **`librosa`**  for audio processing, producing spectrogram and features extraction.
* The **`IPython`** module for displaying the sonification of midi files.
* The midi file [Aligned Scores and Performances (ASAP) dataset](https://magenta.tensorflow.org/datasets/maestro) of scores and performances of Western classical piano music from different composers, its detailed description can be found [here](https://github.com/fosfrancesco/asap-dataset)