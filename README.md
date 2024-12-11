# DeepLaugh
## This project explores the science behind the art of comedy, diving into the captions and audio to identify laughter in comedy videos and identifying the key aspects of comedy videos which lead to more laughs
## Kedar Godbole, Alex Imhoff, Tara Mary Joseph, Jyoti Kumari, Aman Sharma

LaughterAudio.ipynb: Audio analytics file which trains the whisper-small model to predict laughter. Seen in Future Work section of presentation. Uses files: processed_targets_output.csv and mp3 audio files: https://utexas-my.sharepoint.com/personal/as235548_my_utexas_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fas235548%5Fmy%5Futexas%5Fedu%2FDocuments%2Faudio%5Ffiles&ga=1
LLMs were used for this code, to read in files and model.

## Associated python notebooks and files are listed below 

#### Content Downloading - Following File Downloads YouTube audio and captions and saves them in a folder
- **File:** [Subtitle Scraper.ipynb](Subtitle%20Scraper.ipynb)
#### Convert Audio - Following File Converts the Downloaded Audio into MP3 Format
- **File:** File: [Mp3 Converter.ipynb](Mp3%20Converter.ipynb)
#### Cleaning Videos - Following File Cleans the Downloaded Videos to get rid of excess/unnecessary formatting
- **File:** [`Video_scrape_clean_v2.ipynb`](Video_scrape_clean_v2.ipynb)
#### Exploratory Data Analysis - File does some basic EDA and creates graphs (mins per video and laughs per video)
- **File:** [`Video_Clip_EDA.ipynb`](Video_Clip_EDA.ipynb) 
#### Text Analytics
- **File:** [`TextAnalytics_FeaturesModel.ipynb`](TextAnalytics_FeaturesModel.ipynb)
#### Laughter Audio
- **File:** [`laughterAudio.ipynb`](laughterAudio.ipynb)
#### Audio Analytics
- **File:** [`Audio_Analytics_feature_models.ipynb`](Audio_Analytics_feature_models.ipynb)
#### Analytics with Transformers
- **File:** [`transformer_audio_AST.ipynb`](transformer_audio_AST.ipynb)
