# Belly Button Biodiversity
![image](https://user-images.githubusercontent.com/110074895/211963344-156fdf62-4b4a-489a-a58f-a57e244d5747.png)        ![image](https://user-images.githubusercontent.com/110074895/211963849-16ebb23b-3858-47a7-8fd8-35d9cbb1a5bc.png)
)





## Summary
In this assignment, I built an interactive dashboard to explore the Belly Button Biodiversity dataset [https://robdunnlab.com/projects/belly-button-biodiversity/], which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Instructions</br>
The following steps were taken to complete the challenge:</br>

### Step 1: Creating Bar Chart

1.  Used D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

3. Used sample_values as the values for the bar chart.

4. Used otu_ids as the labels for the bar chart.

5. Used otu_labels as the hovertext for the chart.
![image](https://github.com/NTHub23/belly-button-challenge/assets/138403390/ed24359a-a427-45da-af65-09489e44a0b4)


### Step 2 : Creating Bubble Chart</br>

1. Created a bubble chart that displays each sample.

2. Used otu_ids for the x values.

3. Used sample_values for the y values.

4. Used sample_values for the marker size.

5. Used otu_ids for the marker colors.

6. Used otu_labels for the text values.

![image](https://github.com/NTHub23/belly-button-challenge/assets/138403390/2186d98f-1eb9-4b88-b7df-1ce6b73d79b2)


### Step 3 : Displaying Demographic Information</br>

1. Displayed the sample metadata, i.e., an individual's demographic information.

2. Displayed each key-value pair from the metadata JSON object on the page.

![image](https://github.com/NTHub23/belly-button-challenge/assets/138403390/c34cc8f3-0125-4c53-95cf-8c6dc52db060)

3. The code updates all the plots when a new sample is selected.

### Step 4 : Weekly Washing Frequency Gauge</br>
I adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

Then, I modified the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

The final dashboard layout created any layout that you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/NTHub23/belly-button-challenge/assets/138403390/3701b739-f25b-4c7f-99bf-ee06a6686ca7)






