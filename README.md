# visualization-d3-heart
Making data visualization with heart disease data set https://archive.ics.uci.edu/ml/datasets/heart+Disease
with d3.js 

## Chart
1. Scatter Plot
2. Bubble Chart
3. Sankey Diagram
4. Multi Barchart
5. Paraller Coordinates Plot

### Scatter plot
Relationship between Maximum Heart Rate and age based on disease status (target)
Attribut:
* Age (X Axis)
* Thalach (Y Axis)
* Negative for Heart Disease (Green dot)
* Positive for Heart Disease (Red dot)

![sp](https://user-images.githubusercontent.com/32294888/56745095-f3da2200-67a3-11e9-9eb6-d3a5c9b531dd.PNG)


### Bubble Chart
Number of people with heart disease based on age group and anginal pain
Attribut:
* Age group
 * 20s : Blue
 * 30s : orange
 * 40s : green
 * 50s : red
 * 60s : purple
 * 70s : brown
* Number of Patient (Size)
* Anginal-pain (Buble)

![bubble](https://user-images.githubusercontent.com/32294888/56745363-68ad5c00-67a4-11e9-8b91-6521993eaefe.PNG)


###  Sankey Diagram
Showing the flow of each categorical atribut
Attribut:
* Age group (First Column)
* Gender (Second Column)
* Anginal-Pain (Thid Column)
* Heart Disease Status (Fourth Column)
* Number of Patient (Line flow size)


![sd](https://user-images.githubusercontent.com/32294888/56746046-a5c61e00-67a5-11e9-95dd-39645f9ee1f7.PNG)


### Multiple Barchart
Explain number of anginal pain in each gender
Chart:
1. Male
2. Female

Attribut:
* Number of patient (Y Axis)
* Anginal pain category (X Axis) (Color)
 * asymptomatic : Blue
 * atypical angina : yellow
 * non-anginal pain : orange
 * typical angina : red

![mb](https://user-images.githubusercontent.com/32294888/56746451-706e0000-67a6-11e9-87ba-4bcc3704fd8f.PNG)


### Parallel Coordinates Plot
Showing the flow of each numeric
Attribut:
* Age (First Column)
* trestbps (Second Column)
* chol (Thid Column)
* thalach (Fourth Column)
* oldpeak (fifth Column)
* ca (sixth Column)
* Patient (Line)

![pc](https://user-images.githubusercontent.com/32294888/56746631-c8a50200-67a6-11e9-97b6-ff25a3b20ab5.PNG)
