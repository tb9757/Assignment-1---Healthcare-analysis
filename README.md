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
-   Hypothesis 2: Being a smoker increases your insurance charges more than being overweight. I will plot a graph of age against cost and colour for both smoker and bmi (in categories), to see which increases insurance costs by more.
-   Hypothesis 3: Insurance charges are greater in the East of the US than the West. I will compare insurance costs in the east to the west using a compararive chart

## Project Plan

-   Outline the high-level steps taken for the analysis.
-   How was the data managed throughout the collection, processing, analysis and interpretation steps?
-   Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations

-   List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used

-   I have split the BMI category into the 5 different distinctions on the NHS website. When I plotted the graph of age against cost and coloured for BMI I expected it to be clear from the colours whether charges increased with bmi, but it was not. There were too many categories for bmi. In my further analysis I will change the categories to make it so there are two, healthy weight and overweight. Hopefully this will make it clearer
-   How did you structure the data analysis techniques. Justify your response.
-   Did the data limit you, and did you use an alternative approach to meet these challenges?
-   How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations

-   Were there any data privacy, bias or fairness issues with the data?
-   How did you overcome any legal or societal issues?

## Unfixed Bugs

-   Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
-   Did you recognise gaps in your knowledge, and how did you address them?
-   If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

-   What challenges did you face, and what strategies were used to overcome these challenges?
-   What new skills or tools do you plan to learn next based on your project experience?

## Main Data Analysis Libraries

-   matplotlib library and documentation on the boxplots https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.boxplot.html
-   plotly
-   seaborn

## Credits

### Content

-   The description of this project and the dataset context came from the LMS provided by the Code Institute
-   Information on BMI from the NHS website https://www.nhs.uk/conditions/obesity/
-   How to set 3d fig size in plotly https://plotly.com/python/3d-scatter-plots/
-

### Media

-   The photos used on the home and sign-up page are from This Open-Source site
-   The images used for the gallery page were taken from this other open-source site

## Acknowledgements (optional)

-   Thank you to other members of my cohort.
