# English-Accent-Classification-Using-CNN
Having gone through the phase of a newcomer international student in 2022, I have found myself in sitations where I was talking to someone online or on a phone and through no fault of me or the person on the other end of the call, there were a lot of communication gaps that had risen because of differences in the accents and the way people interpret different accents of the gloablly spoken language that is english. This inspired me to work with spectrograms to determine the accent in which a certain audio is being spoken. 

For context, spectrograms are like snapshots of audio which show the amplitude of the audio against time are an interesting way to look at the audio and they can help us determine 

## Requirements
The following command installs all necessary packages:
```bash
pip install -r requirements.txt
```

## Experiment steps
- data exploration and preprocessing;
- MFCC features extraction; (To model characteristics of a human voice better)
- CNN model definition for classification;
- training and inference;
- result analysis.

## Dataset
I utilized a subset of the the dataset that can be downloaded from the link below which is currently hosted on a semi-priavte link on google drive.

For the current research, 742 samples for speaker_1 from **accentdb_extended** version was used. You can download the updated version of the dataset using this [link](https://drive.google.com/drive/u/0/folders/1ffLuWXmQ6LPqMLYMBa6Qh6hwnGs9pqIb).

## Results
The data was trained on the model for 5 epochs which gave me the the accuracy of 98%.



