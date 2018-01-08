The first commit:
#1.5
## EDA-Explore Data Analysis
- 1. find distribution of each feature
- 2. find pearsonr between features
- 3. the number missing value of each features

## Preprocess Data
- 1. delete date
- 2. lop1p
- 3. one-hot (age, gender)
- 4. delete features where there is too much missing value
- 5. fill nan with -999

#1.6
## Preprocess Data
- 1. delete date
- 2. one-hot(age)

offline:0.98649 online:0.8627

#1.7
## Preprocess Data
- 1. long-tail log1p
- 2. delete two valueless features
- 3. add some new statistic features by trian[column] = train[column].apply(lambda x : x - train[column].max())

offline:0.97944 online:0.8854 rank:38
