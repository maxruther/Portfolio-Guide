# Max Ruther's Portfolio
Welcome to my portfolio! Here I document a summary of my data-related projects.
<br></br>

## My Signature Projects

| Project | Tools | Skills Involved | Project Description |
| --- | --- | --- | --- |
| <a href='https://github.com/maxruther/HCP_Fraud_Detection'>**Healthcare Provider Claim Fraud Detection**</a> | Python, Colab | Data Integration, Feature Engineering, Correlation-Based Feature Selection, Oversampling, Exploratory Visualization, Ensemble Learning | Detecting claim fraudulence by healthcare providers, by implementing techniques from relevant literature. |
| <a href='https://github.com/maxruther/Movie-List_Madness'>**Movie-Mad Max's Database and Scrapers**</a> | Python (Pandas, Scikit-Learn, SQLAlchemy, Selenium, BeautifulSoup, Google API), MySQL, Google Calendar  | ETL Processing, Database Management, Validation, Web-Scraping, Automated Search and Relevance Assessment, Review Ratings Analysis, Automated Scheduling Integration | HTML-parsing personal movie journals, review websites, and more to build a MySQL database primed for ratings prediction. |

<br></br>
## All Projects

<br></br>
### Data Analysis & Modelling

| Project | Tools | Skills Involved | Project Description |
| --- | --- | --- | --- |
| <a href='https://github.com/maxruther/HCP_Fraud_Detection'>**Healthcare Provider Claim Fraud Detection**</a> | Python, Colab | Data Integration, Feature Engineering, Correlation-Based Feature Selection, Oversampling, Exploratory Visualization, Ensemble Learning | Detecting claim fraudulence by healthcare providers, by implementing techniques from relevant literature. |
| <a href='https://github.com/maxruther/HCP_Fraud_Detection'>***TMDb* Movie Visualizations**</a> | R, LaTex | Data Visualization, EDA, LaTex Formatting | Analyzing movies' revenue and popularity by genre, with a heavy focus on visualization. A final group project for a _Data Visualization_ course that I completed at DePaul. |
| <a href='https://github.com/maxruther/Emotion-Recognition'>**Emotion Recognition in Images**</a> | Python, Keras, Colab | Image Classification, Neural Networks | Training convolutional neural networks to classify the emotions depicted in frontal images of faces. |
| <a href='https://github.com/maxruther/Movie-List-Madness/blob/cc5ee5efe8f0e06ea3fbe25af422f0142488b71b/Analysis/Predicting%20My%20Ratings%20-%20First%20DT.ipynb'>**Predicting my Movie Ratings**</a> | Python, SQL, JupyterNB | Classification, Review Ratings Analysis | Training a decision tree to classify whether I will enjoy a movie or not, based off the *Metacritic*, *RottenTomatoes*, *IMDb*, and *RogerEbert* review scores. |
| <a href='https://github.com/maxruther/Movie-List-Madness/blob/cc5ee5efe8f0e06ea3fbe25af422f0142488b71b/Analysis/Predicting%20My%20Ratings%20-%20First%20DT.ipynb'>**Predicting my Movie Ratings II**</a> | Python, SQL, JupyterNB | Classification, Review Ratings Analysis | In an attempt to refine my previous decision tree model, I incorporate the films' genre data, as retrieved and parsed from the *Online Movie Database (OMDb)* [in another project of mine](https://github.com/maxruther/Movie-List-Madness/tree/master/omdb_builder). |



<br></br>
### ETL, Database Management, and Web-Scraping: My Movie Project

| Project | Tools | Skills Involved | Project Description |
| --- | --- | --- | --- |
| <a href='https://github.com/maxruther/Movie-List-Madness/tree/master/movielist_ingestion'>**Movie List Ingestor**</a> | Python, SQL/MySQL, Evernote | HTML-Parsing, Data Validation, Defining SQL Procedures, Database Building, Database Management | I parse an HTML version of my personal movie list and load its data into a local MySQL database. |
| <a href='https://github.com/maxruther/Movie-List-Madness/tree/master/omdb_builder'>**Movie Database Enrichment - Incorporating an External Database**</a> | Python, SQL | JSON-Parsing, HTML Requests, Database Management | I enrich my movie list database by drawing from an external, open source one: _The Open Movie Database (OMDb)_. So afforded, I create three new tables in the MySQL database: *OMDb*, *Genres*, and *Critic_Ratings*. |
| <a href='https://github.com/maxruther/Movie-List-Madness/tree/master/RatingsTableMender'>**Movie Database Integrity Improvement: Critical Review Data**</a> | Python, SQL | Handling Missing Values, Data Validation, Database Management | I remedy and supplement the review score data just retrieved from OMDb (as was done in the phase preceding.) These processes, which comprise the critic_ratings.RatingsTableMender package, largely involve remapping missing values and joining in review scores from an additional external source. |
| <a href='https://github.com/maxruther/Movie-List-Madness/tree/master/critic_ratings/scrapers'>**Movie Database Enrichment II - Web-Scraping Additional Reviewers**</a> | Python | Web-Scraping, HTML & CSS Parsing, Web Crawling, Automated Search and Relevance Assessment  | I gather ratings and more from additional reviewers by creating various webscrapers, mainly for *Metacritic* and *Letterboxd*. |
| <a href='https://github.com/maxruther/Movie-List-Madness/tree/master/critic_ratings/scrapers'>**Movie Showtimes - Indie Fandango**</a> | Python, Google Calendar | Web-Scraping, HTML & CSS Parsing, Web Crawling, Automated Search and Relevance Assessment, Automated Scheduling  | I scrape showtimes from the pages of independent movie theaters in Chicago, then schedule them in Google Calendars. |
