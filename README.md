# eeg-driving-attention
can EEG predict attention lapses in a driver the model has never seen?
# Can EEG predict attention lapses in drivers it has never seen?
Drowsy drivers react slowly. This repo tests whether EEG recorded just before a lane-drift event can predict a slow reaction, evaluated on drivers the model never saw during training.

## Data
Multi-channel EEG recordings during a sustained-attention driving task (Cao et al., 2019, figshare): 27 subjects, 32 channels, 500 Hz. A car drifts out of its lane at random and the driver steers back. Reaction time is the label.