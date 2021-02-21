# Introduction

Wrangling is a crucial and perhaps the most tedious step in data analysis. In this project, we gathered data about a twitter page, called WeRateDogs, in multiple formats. The data was then assessed, cleaned, and analyzed. 

# Details    

### Gathering data

There were three  sources of data. 
- The twitter data archive as a csv file.
- Data from the twitter API in json format. 
- The downloaded Image predictions data as a tsv file. <br>     

### Assessing data

Data was assessed for issues using both visual and programmatic methods. Data was visualized in excel. Assessment of issues was done using the followiing criteria:

#### Quality Criteria
- Completeness
- Validity
- Accuracy
- Consistency

#### Tidiness Criteria
- All varaibles are separate columns
- All records are separate rows
- Each group of data is a separate table 

### Cleaning data

The issues found were defined, coded and tested:

# Libraries

The following python libraries were used for the analysis

- pandas
- numpy
- tweepy
- json
- requests