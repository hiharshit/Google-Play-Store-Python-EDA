# Google Play Store Data Analysis (Python EDA)
This repository contains the code and documentation for an Exploratory Data Analysis (EDA) of Google Play Store data using Python.

## Dataset

The dataset used for this analysis can be found [here](https://www.kaggle.com/datasets/lava18/google-play-store-apps). It includes information about apps available on the Google Play Store. Here are the columns in the dataset:

- **App**: Name of the app.
- **Category**: Category of the app (e.g., Education, Entertainment).
- **Rating**: User rating of the app.
- **Reviews**: Number of user reviews for the app.
- **Size**: Size of the app.
- **Installs**: Number of app installs.
- **Type**: Type of the app (e.g., Free, Paid).
- **Price**: Price of the app (if applicable).
- **Content Rating**: Content rating of the app (e.g., Everyone, Teen).
- **Genres**: Genres associated with the app (An app can belong to multiple genres apart from its main category).
- **Last Updated**: Date when the app was last updated.
- **Current Ver**: Current version of the app.
- **Android Ver**: Minimum required Android version for the app.

## EDA File

[Playstore.ipynb](Playstore.ipynb): Jupyter Notebook containing the Python code for the exploratory data analysis of Google Play Store data.

## Usage

You can clone this repository to your local machine and run the Jupyter Notebook to perform the EDA. Make sure you have the required Python libraries installed.

```bash
git clone https://github.com/hiharshit/Google-Play-Store-Python-EDA.git
cd Google-Play-Store-Python-EDA
jupyter notebook Playstore.ipynb
```