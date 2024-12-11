# DeepLaugh
#### DeepLaugh is a study / analysis that explores the science behind the art of comedy, leveraging the captions and audio to identify triggers of laughter in comedy sets







## Associated python notebooks and files are listed below 

#### Content Downloading 
Following File Downloads YouTube audio and captions and saves them in a folder
- **File:** [Subtitle Scraper.ipynb](Subtitle%20Scraper.ipynb)
#### Convert Audio
Following File Converts the Downloaded Audio into MP3 Format
- **File:** File: [Mp3 Converter.ipynb](Mp3%20Converter.ipynb)
#### Cleaning Videos
Following File Cleans the Downloaded Videos to get rid of excess/unnecessary formatting
- **File:** [Video_scrape_clean_v2.ipynb](Video_scrape_clean_v2.ipynb)
#### Exploratory Data Analysis
File does some basic EDA and creates graphs (mins per video and laughs per video)
- **File:** [Video_Clip_EDA.ipynb](Video_Clip_EDA.ipynb) 
#### Text Analytics
- **File:** [TextAnalytics_FeaturesModel.ipynb](TextAnalytics_FeaturesModel.ipynb)
#### Audio Analytics
This notebook processes the audio data to form that can be consumed by tree based models. All details of feature engineering can be found here. Audio files used as the raw input can be found [here](https://utexas-my.sharepoint.com/personal/as235548_my_utexas_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fas235548%5Fmy%5Futexas%5Fedu%2FDocuments%2Faudio%5Ffiles&ga=1)
- **File:** [Audio_Analytics_feature_models.ipynb](Audio_Analytics_feature_models.ipynb)
#### AST Tranformer for Audio modeling
This notebook walks through the execution of AST transformer to predict laughter points.
- **File:** [transformer_audio_AST.ipynb](transformer_audio_AST.ipynb)
#### Combining Models
This notebook walks through the implementation of the DistillBERT model for text, and combines it with the feature based model developed for audio
- **File** [combining_models.ipynb](https://github.com/krgodbole/DeepLaugh/blob/main/combining_models.ipynb)
#### Laughter Audio (Future Scope)
Notebook with implementation of training of the whisper-small model to predict laughter. Seen in Future Work section of presentation. Uses files: processed_targets_output.csv and mp3 audio [files](https://utexas-my.sharepoint.com/personal/as235548_my_utexas_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fas235548%5Fmy%5Futexas%5Fedu%2FDocuments%2Faudio%5Ffiles&ga=1)
- **File:** [laughterAudio.ipynb](laughterAudio.ipynb)





This project was done as a part of capstone project for the course: Adavanced Machine Learning (MIS382N) instructed by Prof. Joydeep Ghosh. Contributors are  Kedar Godbole, Alex Imhoff, Tara Mary Joseph, Jyoti Kumari, [Aman Sharma](https://github.com/aman-uta-kgp)
