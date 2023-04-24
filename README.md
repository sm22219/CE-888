# CE-888
Final Assignment
Link for merged_data_labeled dataset:  https://drive.google.com/file/d/11K3teZz8vmoCav-XO_mu3L8G7rARIYRy/view?usp=share_link
Link for SurveyResult.csv dataset:  https://docs.google.com/spreadsheets/d/13U9DZ_cE0ExqVQkGeVa2BnkP3xOq24bm/edit?usp=share_link&ouid=110820232770859697596&rtpof=true&sd=true
Link for Raw-Dataset:  https://datadryad.org/stash/dataset/doi:10.5061/dryad.5hqbzkh6f
Dataset Description: The primary stress dataset comprises biometric signals obtained from smart wearables used by 15 nurses during their shifts at the hospital. The accompanying survey results contain responses from the participants regarding factors that may have contributed to their increased stress levels while attending to patients. Each nurse's data is organized into separate folders with timestamped versions. The signals were recorded at varying sampling rates, with heart rate (HR) sampled at 1 Hz and blood volume pulse (BVP) at 64 Hz. Accelerometer data and electrodermal activity (EDA) were sampled at 32 Hz and 4 Hz, respectively, while the temperature was recorded at a rate of 4 Hz
Instruction to process raw dataset:- 
---> Unzipping Folder:- set path for nurses_directory and target_directory (section referred as 'First Part')
---> Combining Signals:-  set path for DATA_PATH and SAVE_PATH (section referred as 'Combining the signals into signal specific files respectively')
---> Merging Signals into Single File:-  set path for COMBINED_DATA_PATH and SAVE_PATH (section referred as 'Merging all the signal specific files into a single file (merging features)')
---> Labelling the merged dataset:-  set path for PATH and survey_path(containing the SurveyResult.csv) (section referred as 'Labelling the merged dataset with the help survey results')
