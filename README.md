# ![](https://github.com/BlakeWallace/Project_Pigskin) Project Pigskin

---

<a id='creators'></a>

## Creators
  
[Blake Wallace](https://www.linkedin.com/in/blake-wallace)  

---

<a id='problem-statement'></a>

## Problem Statement

#### Data Scinece Question

Can a model be constructed that picks the winner with at least 75% accuracy?

#### Project Objective

Construct any model that will predict with at least 75% accuracy the winner in any division 1 football game given current data about the teams.  The goal of the model will be to generate a probability of victory for each of two competing teams in order to determine the team that is more likely to win.

#### Current Tasks

1. Find a list of all division 1 college football teams.
1. Obtain basic lifetime stats for each team in the list of Division 1 teams.  (Basic stats include: win-loss-tie record or win percentage, average offensive yards per game, average points per game, average number of touchdowns per game, average number of defensive tackles per game, average number of possessions per game, average number of fieldgoals per game, average number of points allowed, average number of yards allowed, etc.)
1. Obtain the same stats as above, but for only the last 7 years.  The belief is that the near past performence, as opposed to the historical performence, of any given team will be a better predictor of success in current game play.  Seven years will act as a starting point for exploring the ambiguous concept of "near past."
---

## Contents in README
[Creators](#creators)  
[Problem Statement](#problem-statement)  
[Contents in Project Repo](#repo-content)  
[Data Dictionary](#data-dictionary)  
[Executive Summary](#executive-summary)  
[Known Issues](#known-issues)  
[Future iterations/next steps](#next-steps)  
[Data Sources](#data-sources)  
[Sources](#sources)

---

<a id='repo-content'></a>

## Contents in Project Repo
1. [Data](https://github.com/BlakeWallace/Project_Pigskin/tree/master/Data)  
    1. [data_for_analysis](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Data/data_for_analysis.csv)
    1. 
    1. 
    1. 
1. [Notre_Dame_Football](https://github.com/BlakeWallace/Project_Pigskin/tree/master/Notre_Dame_Football)
    1. [Exploring_Notre_Dame_historical_stats](https://github.com/BlakeWallace/Project_Pigskin/tree/master/Notre_Dame_Football/Exploring_Notre_Dame_historical_stats.ipynb)
    1. [notre_dame_football_historical_data](https://github.com/BlakeWallace/Project_Pigskin/tree/master/Notre_Dame_Football/notre_dame_football_historical_data.ipynb)  
1. [Objectives_and_Data_Science_Questions](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Objectives_and_Data_Science_Questions.ipynb)  
1. [Sources](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Sources.ipynb)  
1. [win_loss_tie_data](https://github.com/BlakeWallace/Project_Pigskin/blob/master/win_loss_tie_data.ipynb)  
1. [README.md](https://github.com/BlakeWallace/Project_Pigskin/blob/master/README.md)

---

<a id='data-dictionary'></a>

## Data Dictionary

A few notes regarding the primary dataset used for modeling:
1. The primary dataset for analysis to answer the data science questions is labeled [data_for_analysis](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Data/data_for_analysis.csv).  
1. When reading through a notebook, any data that is put into this dataset is labeled `'stuff_to_keep'`.  Once this point is reached inside a notebook, the data that follows is munged, cleaned, engineered, or explored to be included in the primary dataset for analysis.  In all cases the data is later renamed to be included to the [data_for_analysis](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Data/data_for_analysis.csv) dataset.

**Our primary [data_for_analysis](https://github.com/BlakeWallace/Project_Pigskin/blob/master/Data/data_for_analysis.csv) is displayed in the following table.**

<div align="left"> 
    
|Feature (Bin #)|Description|
|---|---|
file_name|Name of .wav Audio File
class|Emergency or Non-Emergency
emergency_type|Description of Situation
origin|Broadcastify or YouTube
good_exception|Whether or not Speech Detection API detected audio or not
audio_recognition|Speech-to-Text of the Audio Clip
tempogram_#|Tempo
spectral_contrast_#|Spectral Contrast
chroma_cens_#|Chroma Feature Normalized
spectral_centroid|Spectral Centroid
spectral_band|Spectral Bandwidth
spectral_flat|Spectral Flatness
rolloff|Spectral Rolloff
chroma_cqt_#|Chroma Continuous Q Transform
tonnetz_#|Tonnetz
contrast_#|Spectral Contrast
mel_#|Mel Scale
chroma_stft_#|Chroma Short Time Fourier Transform
mfcc_#|Mel Frequency Cepstrum
preds|Model Prediction of Class

</div>

---

<a id='executive-summary'></a>

## Executive Summary



---

<a id='known-issues'></a>

## Known Issues



---

<a id='next-steps'></a>

## Future iterations/next steps



---

<a id='data-sources'></a>

## Data Sources

1. [Sports Reference](https://www.sports-reference.com)   
    1. [CFB School Index](https://www.sports-reference.com/cfb/schools/)
        1. [win-loss-tie data](https://github.com/BlakeWallace/Project_Pigskin/blob/master/win_loss_tie_data.ipynb)  
    1. [Sports Reference's Notre Dame Historical Data](https://www.sports-reference.com/cfb/schools/notre-dame/)  
        1. [Exploring_Notre_Dame_historical_stats](https://github.com/BlakeWallace/Project_Pigskin/tree/master/Notre_Dame_Football/Exploring_Notre_Dame_historical_stats.ipynb)  
---

<a id='sources'></a>

## Sources

1. [Sports Reference](https://www.sports-reference.com)