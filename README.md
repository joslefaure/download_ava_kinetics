# download_ava_kinetics
Script to download AVA kinetics

The code is modified from https://github.com/gurkirt/kinetics-download-prep

To download all the videos at once, run `python download.py --output_dir=your/output/path --input_csv=videos_to_download.csv`.

To download the training videos, run `python download.py --output_dir=train/output/path --input_csv=train.csv`. 

To download the validation videos, replace the `train.csv` with `val.csv` or `test.csv` for the test data

**Note: Every downloaded video lasts 6 seconds (3 seconds before the start of the annotated action) for a better representation of the action. The timestamp of the action is written in the video filename**

**Dependencies:**

    conda install joblib
    conda install pandas
    conda install sqlite
    conda install zlib
    conda install -c menpo ffmpeg
    pip install --upgrade youtube-dl
    
You might also need to install x264 if you don't have it already

`conda install -c conda-forge x264`

