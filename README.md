# Spoken Digit Classification
- **Description:** Implement a classifier able to predict which digit is pronounced in a short audio excerpt.
- **Input:** As dataset use the Free Spoken Digit Dataset (FSDD) which is available at the link:
https://github.com/Jakobovski/free-spoken-digit-dataset
In the folder recodings you will find the audio files named in a specific format. Please read the READ ME distributed with the dataset. The results of the classification must be reported as a confusion matrix and, optionally, other metrics of your choice.
- **Output:**
  - a brief presentation of your work (max 5 minutes) that will be given to the class
  - a more detailed report in which you illustrate and explain every step of your
classification system and in which the results are shown and commented (max 8
pages) to be delivered by May 17th.
  - a link to a repository containing the code (e.g. on GitHub) with minimal comments.


### Tasks:
- [ ] **Preprocessing**
- [ ] Feature selection
- [ ] Dataset split
- [ ] Feature extraction
- [ ] Feature selection
- [ ] Classification
- [ ] Performance evaluation  

## Dataset
- Noise:
Audio data is pretty noisy overall
- Length:
Files have different lengths, some of the files are about 2 seconds long but the meaningful part is like half a second. I suggest to trim the few outliers and zero-pad the others. Having the data with the same length could be useful in a lot of ways, like having temporal/spectral features with the same reference frame and so on.
- Normalization:
Some tracks haven't been normalized, maybe it will be useful to normalize them
- Distribution:
The dataset is well distributed, 200 tracks for each of the 10 labels.

## Features
[Mel-frequency cepstrum coefficients]()  
[Linear Predictive Coding](https://en.wikipedia.org/wiki/Linear_predictive_coding])  
[Phoneme detection](https://dataprivacylab.org/projects/bebe/paper.pdf)  
[HiddenMarkovModels](https://en.wikipedia.org/wiki/Hidden_Markov_model)  
[Image processing on spectrogram](https://www.isca-speech.org/archive/archive_papers/interspeech_2014/i14_2533.pdf)  


## TODO
- Check length issues and workarounds

# Notes
## Preprocess
- [ ] **Normalization (Peak-rms issues)**
- [ ] **zero pad or trimming (outliers or noise)**
- [ ] Pre-emphasis
- [ ] denoising process
## Features
- [ ] **MFCC parameters tuning**
- 
