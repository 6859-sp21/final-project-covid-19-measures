# COVID-19 Government Measures Exploration

### Work Split
I worked individually, and completed all of the work for this project myself.

### Development Process
I came up with this project idea by investigating which COVID-19 related visualization needs were unfulfilled. I realized that, although plenty of visualizations of cases and deaths exist, there was no intuitive and interactive way to see government measures. After finding the interesting dataset from ACAPS, I decided to work on visualizing it.

To begin, I planned my overall application flow. I chose to create two separate visualizations on two separate pages to allow users to explore the data at various levels of granularity. I then determined that a world map was the optimal way to easily display the data at a high level, and a bar chart would work well for a more detailed view. I decided to use d3.js, as it had all of the necessary functionality. 

After implementing the basic visualizations, I thought about which filters and interactions to include. I determined that my chosen filters were the most critical for users, balancing function with simplicity. I then implemented the filters one by one, making sure to stress-test everything before moving on.

At the milestone review, I received a lot of very helpful feedback. In particular, students recommended that I reevaluate my color choices to make the important parts of the data stand out, and add a colorbar to the map. Many also mentioned that clearer instructions would be helpful to guide the user. Some also commented on aesthetics, suggesting ways to rearrange elements on the page. Additionally, I recieved some feedback that a back button on the detailed country page would be useful. I implemented all of these changes, ensuring that I was addressing the major feedback points from the review.

Finally, I cleaned up and tested my visualizations. I also ran an informal user study, having a few people test out my system to ensure I did not miss anything. After making a few final fixes and adjustments, my project was complete. Please see the paper, in particular the Methods section, for more specific details on design decisions.
