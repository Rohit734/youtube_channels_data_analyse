# YouTube Data Analysis Project

## Overview
This project involves conducting exploratory data analysis (EDA) on a dataset containing information about YouTube channels. The dataset includes details such as channel rank, subscribers, video views, video count, category, and start year. The goal of the analysis is to gain insights into various aspects of YouTube channels and their performance metrics.

## Dataset
The dataset used for this analysis is provided in a CSV format. It includes the following columns:

- Rank: The ranking of the channel.
- Youtuber: The name of the YouTube channel.
- Subscribers: The number of subscribers to the channel.
- Video Views: The total number of views on the channel's videos.
- Video Count: The number of videos uploaded to the channel.
- Category: The category or genre of the channel.
- Started: The year when the channel was started.

## Analysis Tasks
The analysis includes the following tasks:

1. Data Cleaning:
   - Handling missing values.
   - Checking and correcting data types.

2. Data Understanding:
   - Describing the dataset.
   - Summarizing central tendency and dispersion of numerical features.
   - Exploring the distribution of categorical features.

3. Data Exploration and Visualization:
   - Creating visualizations to understand the distribution of numerical and categorical features.
   - Exploring relationships between variables using scatter plots, correlation matrices, and other visualizations.

4. ## Insights and Conclusion

    ### Key Findings:
    1. **Subscriber-View Relationship**: There is a strong positive correlation (correlation coefficient: 0.79) between the number of subscribers a channel has and the average number of video views it receives. This suggests that channels with more subscribers tend to attract higher viewership.
    
    2. **Category Performance**: Music and Entertainment categories consistently top the charts in terms of subscriber count and video views. These categories tend to have significantly higher engagement compared to others.

    3. **Upload Frequency**: Channels in the Shows category tend to upload videos more frequently, followed by channels in the Music and Entertainment categories. This suggests that regular content updates may contribute to higher subscriber counts and viewership.

    4. **Impact of Channel Age**: Channels started before 2010 (Early) generally have higher subscriber counts and video views compared to those started more recently (Recent). This indicates that older channels may have had more time to establish a dedicated audience and accumulate content.

### Conclusion:
- The analysis reveals strong correlations between various performance metrics of YouTube channels, such as subscribers, video views, and category types. 
- Channels in popular categories like Music and Entertainment tend to attract more subscribers and views, while upload frequency also plays a role in maintaining audience engagement.
- Understanding these patterns can help content creators and marketers strategize their efforts to optimize channel performance and grow their audience base.


## Tools and Libraries
The analysis is performed using Python programming language and various libraries, including:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Statistics

## Usage
To replicate or extend the analysis, follow these steps:
1. Clone this repository to your local machine.
2. Install the required libraries mentioned in the `requirements.txt` file.
3. Run the Jupyter Notebook `YouTube_Data_Analysis.ipynb` to execute the analysis steps.

## Author


