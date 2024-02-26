### Urdu-Speech-Recognition

#### Speech Processing Project

##### This project is a continuation of my journey with speech recognition models. However, the nature of the problem and the data collection process used were different in this project. The unsupervised speech processing project was a mixed-methods approach to developing our Urdu speech recognition model. There were two phases of this project. In the data collection phase, I used Praat software to record 708 different sentences to build a phonetically rich Urdu corpus. All my sentences were recorded separately in the same environment at a sampling frequency of 16000 Hz and cleaned for any background noise. In the analysis phase, my recordings were split into 80:20 train-test sets, and the training dataset was passed through the pre-trained wav2vec2 model to develop Urdu speech recognition. I repeated the process using different training weights on the test data and recorded the best word error rate of 0.63. This project taught me how to build a qualitative dataset and use it to develop an assistive model that is helpful to any low-literate Urdu-speaking population.
