# UCI-Power-Plant
The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the plant was set to work with full load.

## [See Notebook](http://nbviewer.jupyter.org/github/ArthurLu/UCI-Power-Plant/blob/master/PySpark%20-%20Power%20Plant.ipynb)
![](http://content.caiso.com/outlook/SP/ems_small.gif)

## Project Highlights
 * Demonstrated the end-to-end process of performing Extract-Transform-Load with PySpark.
 * Performed Exploratory Data Analysis on a real-world dataset, and then applying several different machine learning algorithms to solve a supervised regression problem on the dataset.

## General Description
Power generation is a complex process, and understanding and predicting power output is an important element in managing a plant and its connection to the power grid. The operators of a regional power grid create predictions of power demand based on historical information and environmental factors (e.g., temperature). They then compare the predictions against available resources (e.g., coal, natural gas, nuclear, solar, wind, hydro power plants). Power generation technologies such as solar and wind are highly dependent on environmental conditions, and all generation technologies are subject to planned and unplanned maintenance.

The power output of a peaker power plant varies depending on environmental conditions, so the business problem is predicting the power output of a peaker power plant as a function of the environmental conditions -- since this would enable the grid operator to make economic tradeoffs about the number of peaker plants to turn on (or whether to buy expensive power from another grid).
