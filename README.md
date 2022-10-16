# COGS138 Music
Research into music and emotion.

## Files
`FinalProject-GroupMusic.ipynb` Contains the final code and writeup for the project.

## Overview
Our group wanted to explore the relationship between neural features associated with objective qualities of music, specifically the mean of the alpha, beta, and theta waves respectively of the EEG and mel frequency cepstral co-efficients (MFCC) of the music files. First the MFCC was collected from the .wav files containing the musical stimuli. Next, time frequency power spectral data using Welch's method was gathered from the data and, after narrowing the EEG data to the Cz electrode channel, the mean of the alpha, beta, and theta waves were collected. Lastly, we took the Pearson and Spearman correlations between the mfcc of the musical stimuli and the mean of the alpha, beta, and theta waves respectively of the EEG.

We wanted to look in to certain features related to power in the audio features of the songs in these readings as well. We narrowed down our analysis to MFCC, melspectogram, spectral rolloff, and spectral bandwidth, all of which can be extracted from audio files using the Librosa library.
