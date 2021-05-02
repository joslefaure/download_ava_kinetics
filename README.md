# download_ava_kinetics
Script to download AVA kinetics

The code is modified from https://github.com/gurkirt/kinetics-download-prep

To download all the videos at once, run `python download.py --output_dir=your/output/path --input_csv=videos_to_download.csv`
To download the training videos, run `python download.py --output_dir=train/output/path --input_csv=train.csv`. 
To download the validation videos, replace the `train.csv` with `val.csv` or `test.csv` for the test data

