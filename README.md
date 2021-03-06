# COVID Vulnerability in Cook County
Estimating COVID-19 Vulnerability - Static Map

The COVID-19 Vulnerability Score was calculated by assessing the following characteristics for each census tract in Cook County:

Median Age,
% Living in Group Quarters (nursing homes, dorms, jails, etc.),
% of Households Living Below the Poverty Rate,
% of Population Uninsured,
% of Crowded Households (more than 1 person per room),
% of Population with a Disability,
% Non-White Population.

For each of these seven characteristics, the values were distributed into five classes using the Jenks Methods of distributing values. Values in the lowest of the classes when compared to all tracts were given a score of 1 while values in the highest class were given a score of 5. For example, a census tract with the highest percentage of people living in group quarters as compared to all tracts would be given a score of 5. Finally, scores for all seven population characteristics were summed together, producing a possible vulnerability score ranging from 7 - 35 (if a tract scored all 1's or all 5's respectively). The distribution of vulnerability scores were then grouped one final time into seven categories using the Jenks Method, producing an easier to interpret vulnerability score range of 1-7.

#The HTML webmap was created using the QGIS2Web Plugin
