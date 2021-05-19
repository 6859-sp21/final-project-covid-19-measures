# COVID-19 Government Measures Exploration
## About
Developed by Albert Gerovitch

Deployed GitHub Pages URL: https://6859-sp21.github.io/final-project-covid-19-measures

Project paper: https://6859-sp21.github.io/final-project-covid-19-measures/final/FinalPaper.pdf

Video: https://youtu.be/8yFJH90CAks

## [Project Page](https://6859-sp21.github.io/final-project-covid-19-measures/about.html)

## Abstract
As the COVID-19 pandemic spread around the world, many governments attempted a variety of mitigation strategies to curb the rise of cases and deaths in their countries. Some were more successful than others, but there exists no easy way of exploring these measures to investigate these important trends. We develop an interactive visualization to enable quick and simple exploration of pandemic-related measures by governments worldwide. This tool combines data on COVID-19 cases, deaths, and hospitalizations with detailed information about COVID-19 measures. Using the visualization, users can first browse the data at a high level on a world map and then narrow down to see more granular information about their country of interest. To avoid overloading the user with a multitude of confusing content and features, we emphasize simplicity as well as functionality. In particular, the tool targets policymakers to inform their decisions on future measures to implement. Indeed, we find that users can quickly and easily use our visualization to answer questions about COVID-19 measures. For example, a user can discover insights about measures the United States implemented around the second wave during summer 2020. The tool can be further improved and refined with more data, such as granular state-level measures.

## Work Split
I worked individually, and completed all of the work for this project myself.

## Development Process
I came up with this project idea by investigating which COVID-19 related visualization needs were unfulfilled. I realized that, although plenty of visualizations of cases and deaths exist, there was no intuitive and interactive way to see government measures. After finding the interesting dataset from ACAPS, I decided to work on visualizing it.

To begin, I planned my overall application flow. I chose to create two separate visualizations on two separate pages to allow users to explore the data at various levels of granularity. I then determined that a world map was the optimal way to easily display the data at a high level, and a bar chart would work well for a more detailed view. I decided to use d3.js, as it had all of the necessary functionality. 

After implementing the basic visualizations, I thought about which filters and interactions to include. I determined that my chosen filters were the most critical for users, balancing function with simplicity. I then implemented the filters one by one, making sure to stress-test everything before moving on.

At the milestone review, I received a lot of very helpful feedback. In particular, students recommended that I reevaluate my color choices to make the important parts of the data stand out, and add a colorbar to the map. Many also mentioned that clearer instructions would be helpful to guide the user. Some also commented on aesthetics, suggesting ways to rearrange elements on the page. Additionally, I recieved some feedback that a back button on the detailed country page would be useful. I implemented all of these changes, ensuring that I was addressing the major feedback points from the review.

Finally, I cleaned up and tested my visualizations. I also ran an informal user study, having a few people test out my system to ensure I did not miss anything. After making a few final fixes and adjustments, my project was complete. Please see the paper, in particular the Methods section, for more specific details on design decisions.

## Datasets

[OWID COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)

[ACAPS COVID-19 Government Measures Dataset](https://www.acaps.org/covid-19-government-measures-dataset)