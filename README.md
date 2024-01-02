## A short explanation for what the files consist of:

<p>data-kopi.ndjson<br>
  - The raw file for all the 5000 human stories from reddit
<p>stories_promot_1_final-kopi<br>
  - The raw file for all the 5000 ai stories created using the Stable Beluga model
<p>Data_clean_and_merge-kopi<br>
  - R file for cleaning the stories, e.g. for double spacing etc, and for merging the 2 datasets into 1
<p>data_for_ML-kopi<br>
  - The CSV filed saved from Data_clean_and_merge-kopi to be used in the ML process following. The file contains all the story prompts, completions and type (human or machine) 
<p>Classifying_texts-kopi<br>
  - Jypyter script containing code for the feature extraction and creating and evaluating the 5 ML models
<p>Choosing_random_stories-kopi<br>
  - R file containing code for choosing 30 random ai and 30 random human stories for the online experiment. Afterwards the stories are manually cleaned for errors if needed.
<p>sosci_story_df_real-kopi<br>
  - A csv file with the 60 cleaned stories to be used in the online experiment. The online experiment is coded and carried out using the software SoSci
<p>final_data_from_sosci-kopi<br>
  - A raw csv file with all data collected in through sosci. The file contains 1 row per participant
<p>SoSci_data_analysis-kopi<br>
  - R file containng code for cleaning and restructuring the final_data_from_sosci file as well as analysis of the data


**Note that all files are named -kopi, meaning that if the scripts/files are downloaded and runned, the names should accordingly be changed**

### Feel free to contact me at 202104722@uni.au.dk if any questions or comments emerge
