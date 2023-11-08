# AudioCaps (Japanese)

## Description
There are 4 columns in the csv file.
- **audiocap_id**: The id unique to the audio clips and its corresponding caption.
- **youtube_id**: The youtube clip that the audio belongs to. You can use this to obtain the VGGish embedding from AudioSet.
- **start_time**: The start time of the clip.
- **caption**: The audio caption.

We have two training data sets. Note that some sentences are failed to translate. We dropped the sentences from the csv files.
- **manual (train.csv)**: translated from English by a Japanese native speaker
- **auto (train_auto.csv)**: translated by ChatGPT (gpt-3.5-turbo)

## Statistics:

| Split            |       Count |
| :--------------- | ----------: |
| Train            |      49,838 |
| Validation       |         495 |
| Test             |         975 |
| **Total**        | **51,308** |


Last edit: Nov. 10, 2023
