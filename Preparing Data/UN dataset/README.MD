# Introduction

In this project, I explore the sample data of refugee migration and administrative cost in 2021. The data is obtained from the ExploreAI Data Analytics course and shows the number of refugees, the countries hosting them, the assistance provided by the UNHCR, and the associated costs. I use different types of formulae as well as graphs and maps i Google sheets to visualise the data and reveal some interesting insights. [Explore file here](https://docs.google.com/spreadsheets/d/1ky8ATtA07hN28YCfKblYm2Jp6PxkF-NJ/edit?usp=sharing&ouid=108371581388584348202&rtpof=true&sd=true)

## Data Source

The data is acquired from course files. The file contains the following columns:

- `Country or territory of asylum or residence`: The name of the country hosting the refugees
- `Country or territory of origin`: The name of the country the refugees come from
- `Refugees`: The number of refugees in the host country
- `Refugees Assisted UNHCR`: The number of refugees assisted by the UNHCR in the host country
- `Administrative Cost to Host`: The administrative cost of hosting the refugees in the host country

The data covers 163 host countries and a total of 20.82 million refugees.

## Data Analysis

To analyse the data, I use Google sheets to perform the following steps:

1. Load data in Google sheets.
2. Group data via pivot tables by Territory of assylum and by Territory of origin.
3. Sort the data by the number of refugees.
4. Explore aggregates of the numeric data and summaries of interesting statistics to gain an aunnderstanding of data.
5. Generate Key statistics using conditional formulae, and lookup functions.
6. Visualise Key statistics with scorecard chart.
7. Display map of countries with refugee concentrations as color intensity.

The main findings of the analysis are:

- The UNHCR was only able to assist 50% of the refugees in 2021
- The average cost to host by territory was 3 billion
- Turkey hosted the most refugees (3.68 million) expending 73.9 billion.
- Most refugees generally came from Syria (32.47%).
- Uganda assisted the most refugees (1.41 million).
- There was a wide variation in the cost to host refugees, and some countries spent much more than others to assist refugees.
- Turkey had the highest administrative cost to host refugees ($73.94 billion), which was 2818% above the average.
- Turkey hosted refugees with no assistance from the UNHCR.

## Data Visualization

To visualize the data, I use charts and maps in Google. I create the following graphs and maps:

- A world map showing the territories of asylum in red, with numbers indicating how many refugees are in each country
- A simple table chart showing the top 10 host countries, ranked by the number of refugees they host, and how many refugees are assisted by the UNHCR in each country
- A scatter plot showing the relationship between the cost to host and the number of refugees assisted, with a trend line
- A statistic showing the percentage of refugees from Syria and the administrative cost to host refugees in Turkey


The visualisation is shown below:

![UN data set visual](/assets/Preparing%20Data/UN%20dataset/Screenshot%202024-01-16 135311.png "A complex visualisation of the UN world migration data for 2021")
