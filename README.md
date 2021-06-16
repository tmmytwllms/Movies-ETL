# Movies-ETL

### Resources
- wikipedia-movies.json
- ratings.csv
- movies_metadata.csv
- Wikipedia
- Kaggle

### Software
- Microsoft Excel 2019
- Python 3.8.5
- Anaconda

## Purpose
The purpose of this project was to take several different data sources and put them through the ETL, extract-transform-load, pipeline. Data sources consisted of a metadata csv found from the Kaggle website, a csv of movie ratings, and a json of movie data from Wikipedia. These three data sources were first extracted, and then transformed by changing data types, adding or removing rows, and changing column info using regex epxressions to find patterns. These three sources, once transformed, were merged, and transformed again by removing unnecessary columns and renaming the remaining columns. Lastly, this data was updated to an SQL database so query functions can be performed on it.
