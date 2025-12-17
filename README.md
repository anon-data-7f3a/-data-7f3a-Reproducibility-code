# Anonymous ACL Submission

This repository contains code for an anonymous ACL submission.

## Datasets

Due to GitHub file size limitations, the datasets used in this work are hosted externally.

All analyzed datasets required to reproduce the experiments are available at the following anonymous Hugging Face account:

https://huggingface.co/anon-data-7f3a

The datasets are provided with generic names and descriptions to preserve double-blind review.  
Please refer to the corresponding dataset cards on Hugging Face for download instructions and file structure.


## Setup
pip install -r requirements.txt

## Data
Due to licensing restrictions, datasets are not redistributed.
Instructions for obtaining the data are provided in `scripts/download_data.sh`.

## Run
python train.py --config configs/default.yaml

## Notes
All identifying information has been removed for double-blind review.
