Audio Patter Extractor-Generator in Python

We take a wav file of a given bmp, we split it into beats (training beats, let's call them) and extract audio features
(using https://github.com/tyiannak/pyAudioAnalysis by Theodoros Giannakopoulos) for each beat. 
We use k-means to cluster the beats according to these features. We use this clustering to classify the beats from other wav files and we generate a sequence of beats related 
to this new file but played by the training beats.
