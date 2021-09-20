# Blood-Donor-Prediction
Blood loss is common in many injuries and even in medical operations. Therefore ensuring a proper supply of blood to the blood bank is necessary. Hence blood donation is a very important thing.
This project aims at predicting whether or not a person is willing to donate blood, the next time a blood donation camp is organised.
## Dataset
Our dataset contains 748 entries.
With columns titled Recency,Frequency,Amount of blood donated, whether donated the blood last time or not.

## Libraries used
- Pandas: It was used to read, clean and sort the dataset.
- Sklearn: It was to split the dataset into train class and test class.
- Tpot: The TPOTClassifier from tpot was used to predict the best pipeline that should be used to fit the current dataset.
