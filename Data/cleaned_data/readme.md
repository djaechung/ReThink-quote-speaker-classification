In the original repo, this folder housed the final cleaned data, ready for use in classification models. Open distribution of this data was not permitted, so in this public repo the data is witheld.

Contents would have been:
- `GNI88_cleaned_data.csv` - this dataset is the result of `gni88 02DEC21.json.zip`[full texts] and `GNI88.csv`[labelled, quote-level data] being run through the `fulltext_and_source_data_cleaning.ipynb` notebook, which cleans the full texts, cleans the source names in the labelled data, and adds the full texts to the labelled data as a column
- `GNI88_cleaned_sample.csv` - a sample of 2,000 rows from the full dataset for familiarization purposes and use in EDA/feature creation stages. This sample dataset was created with `Data/data_cleaning_scripts/make_sample_dataset.ipynb`
