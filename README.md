# Deep-Fake-Detection
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. 

## Dataset
The data is comprised of .mp4 files, split into compressed sets of ~10GB apiece. A metadata.json accompanies each set of .mp4 files, and contains filename, label (REAL/FAKE), original and split columns, listed below under Columns.

https://www.kaggle.com/c/deepfake-detection-challenge/data

train_sample_videos.zip - a ZIP file containing a sample set of training videos and a metadata.json with labels. the full set of training videos is available through the links provided above.

sample_submission.csv - a sample submission file in the correct format.

test_videos.zip - a zip file containing a small set of videos to be used as a public validation set.
