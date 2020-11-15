# wildfire_data

Data sources:
1. https://www.kaggle.com/rtatman/188-million-us-wildfires


#### Notebook summary:
generate_data_with_target: resources to generate
(1) a 20k row data sample from the large kaggle sqlite dataset
(2) a 892007-row dataset from the large kaggle sqlite dataset which requires the following features to be present:
	DISCOVERY_TIME, CONT_TIME, DISCOVERY_DATE, and CONT_DATE

calc_cont_time: calculates our target variable of delta in containment time from the four features listed above (DISCOVERY_TIME, CONT_TIME, DISCOVERY_DATE, and CONT_DATE)



