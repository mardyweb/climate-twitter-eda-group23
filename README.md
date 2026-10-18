# Climate Change Twitter: Data Cleaning and EDA
 
CS334 Course Project, Checkpoint 3 · Group 23: Maryam, Izza, Izzah, Noor
 
Data cleaning and exploratory analysis of 15.8 million climate-related tweets (2006–2019), looking at how the volume, topics, tone, stance and geography of the climate conversation changed over time, and whether unusually hot or cold months show up in what people tweet.
 
## Dataset
 
The Climate Change Twitter Dataset (Effrosynidis et al., 2022), available on [Kaggle](https://www.kaggle.com/datasets/deffro/the-climate-change-twitter-dataset). It is not included in this repo because of its size.
 
15,789,411 tweets with 10 columns: `created_at`, `id`, `lng`, `lat`, `topic`, `sentiment`, `stance`, `gender`, `temperature_avg` (temperature anomaly vs the 1951–1980 average), `aggressiveness`.
 
## Contents
 
- `Climate_Change_Twitter_EDA_Group23.ipynb` — the full notebook with all outputs: loading, data-quality checks, cleaning, and 29 analysis sections.
## How to run
 
1. Download `archive.zip` from the Kaggle page above and place it in the same folder as the notebook.
2. Install the requirements: `pip install pandas numpy matplotlib`
3. Open the notebook in Jupyter or VS Code and run all cells.
The file is read in chunks of 500,000 rows, so it runs on a normal laptop (under 3 GB of RAM). The full pass in section 5 takes about 10–25 minutes.
 
## Questions explored
 
1. How did the climate conversation change from 2006 to 2019 (volume, topics, sentiment)?
2. Are tweets from deniers more aggressive than tweets from believers?
3. Did political topics grow, and did stance polarise and aggressiveness rise with them?
4. Does the gender gap in denial hold across regions?
5. Are the same topics linked to denial and aggression in every region?
6. Do unusually hot or cold months change what people talk about, and does this differ by stance?
## Citation
 
Effrosynidis, D., Karasakalidis, A. I., Sylaios, G., & Arampatzis, A. (2022). The climate change Twitter dataset. *Expert Systems with Applications*, 204, 117541. https://doi.org/10.1016/j.eswa.2022.117541
 
