# Project: eeg-driving-attention
Question: can pre-event EEG (e.g. theta/alpha power) predict slow reaction times in unseen drivers?
- Data lives OUTSIDE the repo: C:\data\eeg\driving\ (32 ch, 500 Hz, simulated driving with lane-drift events). Never commit data.
- Always split by SUBJECT. Trials from one driver must never be in both train and test.
- Windows, conda env "medimg", CPU only.
- I am learning: explain what you change and why, keep code simple and commented.