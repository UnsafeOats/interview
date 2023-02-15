# Datasets

## Diseases Dataset
### disease.csv
YearStart\
YearEnd\
LocationAbbr\
LocationDesc\
DataSource\
Topic\
Question\
Response\
DataValueUnit\
DataValueType\
DataValue\
DataValueAlt\
DataValueFootnoteSymbol\
DatavalueFootnote\
LowConfidenceLimit\
HighConfidenceLimit\
StratificationCategory1\
Stratification1\
StratificationCategory2\
Stratification2\
StratificationCategory3\
Stratification3\
GeoLocation\
ResponseID\
LocationID\
TopicID\
QuestionID\
DataValueTypeID\
StratificationCategoryID1\
StratificationID1

## State Income Dataset
### state_income.csv
state\
median_income\
std_error

# Tasks & Questions
1) Read both datasets into dataframes.
2) Provide a full list of possible values for the `Topic` column in the `Diseases` dataframe.
3) Provide a list of counts for each value of `Topic` column in the `Diseases` dataframe. (Bonus: can you plot them as a histogram?)
4) Looking at the `Diseases` dataframe, what is the relationship between the `DataValueType` column and the `DataValue` column?  How should we treat values in the `DataValue` column to accurately represent the data?
5) Filter the `Diseases` dataframe on to only show crude prevalence rates for chronic liver disease mortality.
6) How many missing values are present for the `DataValue` column for the filtered dataset?
7) Cast `DataValue` column to `double` or `float` and impute `0.0` for missing values.
8) Looking at the `State Income` dataset, what would be the appropriate column to join on to find out if there's a relationship between state median income and crude prevalence rate of chronic liver disease?
9) Join the two dataframes on the appropriate columns.  How many states are missing crdue prevalence rates for chronic liver disease mortality?
