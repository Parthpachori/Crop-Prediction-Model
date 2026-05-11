# Agricultural Crop Recommendation System
This project aims to develop a system that recommends suitable crops for cultivation based on various environmental factors. By analyzing parameters such as Nitrogen (N), Phosphorus (P), and Potassium (K) ratios in the soil, along with temperature, humidity, pH level, and rainfall, the system provides data-driven crop suggestions to optimize agricultural yield and sustainability.
# Dataset
The dataset used for this project contains information about various crops and the optimal environmental conditions for their growth.

Source: The dataset was loaded from a local zip file named archive (11).zip. The original source is not explicitly mentioned in the notebook.
Shape: The dataset has 2200 rows and 8 columns.
Features: The dataset includes the following columns:\
N: Ratio of Nitrogen in the soil\
P: Ratio of Phosphorus in the soil
K: Ratio of Potassium in the soil
temperature: Temperature in Celsius
humidity: Relative humidity in percentage
ph: pH value of the soil
rainfall: Rainfall in mm
label: The type of crop (Target variable)
# Model Building and Evaluation
A Logistic Regression model was used for crop recommendation. The dataset was split into training and testing sets (80/20 split).

The model was evaluated using a confusion matrix and classification report, achieving an accuracy of 97%.

# Data Exploration Summary
The dataset contains information on 22 different crops, with 100 samples for each crop.

Key findings from the data exploration include:

Average ratios of Nitrogen, Phosphorus, and Potassium in the soil.
Average temperature, humidity, pH, and rainfall.
Identification of crops requiring high/low levels of certain parameters.
Identification of crops suitable for summer, winter, and rainy seasons based on temperature and humidity.
