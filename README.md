# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Healthcare Insurance Cost Analysis

**Healthcare Insurance Cost Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

The purpose of this project is to analyse healthcare insurance data to understand how personal attributes and geographic factors influence insurance costs and develop predictive models for estimating healthcare expenses. Provide insights and predictive reports for estimating healthcare insurance charges based on personal and geographic attributes.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

The dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits) and geographic factors and their impact on medical insurance charges. This data can be used to study how these features influence insurance costs and develop predictive reports for estimating healthcare expenses.

## Business Requirements

-   I am looking to use this dataset to be able to predict the cost of insurance based on different characteristics and circumstances.

## Hypothesis and how to validate?

-   Hypothesis 1: On average, men pay more in insurance charges than women. I will calculate the average cost of insurance for both men and women and compare them in a chart.
-   Hypothesis 2: Being older increases your insurance charges more than being overweight. I will use a correlation heatmap to see which correlates more with charges
-   Hypothesis 3: Insurance charges are greater in the East of the US than the West. I will compare average insurance costs in the east to the west.

## Project Plan

-   My plan is to examine the data, looking for null values, checking data types and thinking about if there is any feature creation I could undergo to make any interesting conclusions from the data.
-   I indend to split the regions into north and south as well as east and west. I also categorised BMI by using the NHS guidlines for the different categories.
-   I will make a boxplot to investigate if there were any outliers in the data
-   I will use scatter plots and correlation heat maps to see the correlation between the data. If there is a correlation between the data it can be easily seen using the scatterplots. If it is harder to see you can visualise it with a correlation heatmap.
-   I want to use the scatter plots to be able to predict insurance charges, so I will use an interactive plotly chart, which allows you to hover over the data to see the values

## The rationale to map the business requirements to the Data Visualisations

-   Using the plotly interactive plots you should be able to predict the insurance charges based on age, BMI and smoker status.

## Analysis techniques used

-   I have split the BMI category into the 5 different distinctions on the NHS website. When I plotted the graph of age against cost and coloured for BMI I expected it to be clear from the colours whether charges increased with bmi, but it was not. There were too many categories for bmi. In my further analysis I will change the categories to make it so there are two, healthy weight and overweight. Hopefully this will make it clearer
-   I started with the more simple matplotlib plots, then moved onto seaborn for the correlation analysis and finally plotly for the predictive analysis as it is more interactive so more useful in predictions.
-   There are more factors to consider than just the ones in this dataset when deciding the insurance charges, so I would say that the dataset is limited.
-   I promted Chat GPT not to show me any code, but to act as a mentor and help me though any tasks. I prompted it to ask me questions and give hints rather than tell me answers. I would then have a go at the code and use it to help me debug.

## Ethical considerations

-   This data may refer to real people and it is important to condiser this when analysing the data. Bits of this dataset are sensitive information, particulatly BMI and number of children. It is important that these data are annonomysed, which they seem to be.
-   It is also important to consider how making a model with this dataset may re-inforce historical bias, such as charging smokers or people with higher BMI more for insurance without considering the social context of the individuals.

## Unfixed Bugs

-   Bugs were fixed as I went along with help from Chat GPT, there should not be any currently in the code

## Development Roadmap

-   There were lots of challenges along the way. Including some problems that I solved which it turns out I didn't need to do at all. All of which was good revision of how to use pandas and the different visualisation softwares.
-   I would like to better understand statistics as I found that I got stuck at the knowing what to plot stage. It would be good intuitively what sort of columns should be plotted against each other to make the results mean something and be interesting to look at.
-   I would also like to be better at coming up with hypotheses.

## Main Data Analysis Libraries

-   matplotlib https://matplotlib.org/
-   plotly https://plotly.com/python/
-   seaborn https://seaborn.pydata.org/

## Conclusions

-   Hypothesis 1: On average, men pay more in insurance charges than women.

There did seem to be a higher average charge for men than women, I wanted to investigate this further but could not due to time constraints. Is it because more men smoke?

-   Hypothesis 2: Being older increases your insurance charges more than being overweight.

There was a slightly higher correlation between age and charges than beterrn bmi and charges, so it can be said that being older effects your insurance charges more than being overweight

-   Hypothesis 3: Insurance charges are greater in the East of the US than the West.

The charges in the East were greater than the west, maybe this is because New York is located in the west, or maybe it is something to do with the population density

## Credits

### Content

-   The description of this project and the dataset context came from the LMS provided by the Code Institute
-   Information on BMI from the NHS website https://www.nhs.uk/conditions/obesity/
-   How to set 3d fig size in plotly https://plotly.com/python/3d-scatter-plots/
-   How to set bar colours https://matplotlib.org/stable/gallery/lines_bars_and_markers/bar_colors.html
-   How to add labels in plotly https://plotly.com/python/figure-labels/

### Media:

-   N/A

## Acknowledgements (optional)

-   Thank you to other members of my cohort.
