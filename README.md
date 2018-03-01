# DSB_2018
Data Science Bowl 2018

## Lucas U-Net Instructions:
1. SSH into the server, using your own account
2. Clone this repository into your folder
3. `source activate dsb` (shared conda environment)
4. `cd lucas-u-net`
5. `python train.py`: this should create a .csv file that you can then submit on Kaggle.

(You might have to create an empty folder called numpy_dumps in "DSB_2018" if it gives you an error about the directory being non-existent. This is where the pre-processed data gets stored for later use.)

The raw data itself is stored at `/hdd/datasets/datasciencebowl2018/`.
