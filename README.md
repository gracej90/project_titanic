#### Summary

The visualizations explore the relationship between survival rates of passengers aboard Titanic and passenger information such as age. From the analysis, you can see the following: 1) lower class (i.e. 3) has lower survival rate, 2) while for females, older age groups have higher survival rates, for males, survival rates range around 20% for adults. The dataset contains demographics and passenger information from a subset of 2224 passengers and crew onboard the Titanic. More information about dataset can be found [here](www.kaggle.com/c/titanic).

#### Design

Following details on iterations explain the design choices I made before and after collecting feedback.

In the 1st iteration, I drew 2 bar charts showing survival rates by passenger class and age group. As both class and age group were categorical variables, bar charts made most sense (note: age, a continuous variable was grouped for analysis). Next, to explore whether there is a difference in survival rate between females and males, I added the sex variable to the chart. Bars were stacked next to one another for easy comparison.

In the 2nd iteration, interactivity was added. Instead of simply displaying the legends, now if viewers wanted to focus only on females for example, they can click and change the chart accordingly.

In the final iteration, a 3rd chart was added to take a closer look at survival rate by age groups. Here I chose the bubble graph to easily show how the age groups compare to one another. Unlike the 2nd chart, the chart animates back and forth automatically to emphasize the wide disparity between females and males. Viewers have the option to click bars on the right and pause the animation.

#### Feedback

* Bar charts of survival rate by Class & Sex (1st iteration)
    * "It would be nice if I can interact with the legend. For example, if I wanted to look only at females."
    * "You should change the axis titles so they are more informative?"
* Bar charts with interactivity (2nd iteration)
    * "This is great. But I'm curious about total number of passengers for each sex. Maybe the survival rate was lower for males because there were more of them?"
* Closer look at age groups (final iteration)
    * "Can you order the legend so it is easier to follow?"

#### Resources
https://discussions.udacity.com/t/dynamic-buttons-between-cabin-class-and-sex/177482/14
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
