# alexnet_based_malimg
This is an implementation of alexnet based malware image based malware image classification




-----------------------------------------------------------------------------------------------------------------------------------------------------------

Dataset links
-----------------------------------------------------------------------------------------------------------------------------------------------------------









-----------------------------------------------------------------------------------------------------------------------------------------------------------
ABOUT IPYNB NOTE BOOKS
-----------------------------------------------------------------------------------------------------------------------------------------------------------

THIS IS PART OF THE TERM PROJECT. IT WILL REALLY HELP OF ONE READS THE PAPER TO BETTER UNDERSTAND THIS.

IT HAS THE FOLLWING PARTS:


DATA AUGUMENTAION CODE --- THIS IS TO DO THE PRE-PROCESSING STAGE...ACCODIGN TO THE PAPER
    ----- IT CREATES A DATASET OF 1000 SAMPLES IN EACH FOLDER.
  
ALEXNET FEATURE EXRTRACTION:---- IT IS USED TO EXTRACT FEATURES FROM ALEXNET
      ----- IT EXTRACTED FEATRUES OF 1000 SAMPLES FROM THE FILES

ALL FEATURES FILES
        THIS FILE EXTRACTS FEATURES FROM OTHER 4 PRE-TRAINED MODELS
        IT RESULTS FOUR FOLDERS NAMED AFTER THE MODELS..EACH WITH 100 SAMPLE POINTS TENSOR FILESD


RANDOM FOREST ON ALEXNET
      THIS IS THE FILE THAT APPLIES RANDOM FOREST ALGORITHM ON THE FEATURE DATASET CREATED BY ALEXNET...EACH 1000 SAMPLES
      IT GIVE A RESULT OF 97% ACCURACY
        
RANDOM FOREST ON ALL THE FILES
      THIS IS THE ML CLASSIFICATION PART ON THE METHOD, AS DETAILDE ON THE PAPER
      IT SIMPLY APPLIES RANDOM FOREST ON THE SAMPLES EXTRACRTED FROM THE MODELS...ON 100 SAMPLES EACH
