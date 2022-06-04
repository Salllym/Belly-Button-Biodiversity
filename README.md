# Belly-Button-Biodiversity
Data Analysis to build an interactive dashboard exploring the Belly Button Biodiversity Dataset using Plotly.js

Please view the live file here:


## Background

Build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Please view the live file here:

## Ojective

Create an interactive visualization using JavaScript to display information about the biodiversity of belly button bacteria on a webpage. The volunteers can look up their individula data by the ID numbers provides to them. The resources provided by GitHib were used to host the files for anyone to view.

## Technologies Used
* Javascript
* plotly
* html5
* bootstrap4
* css3
* json 

* Data Sources: samples.json, index.html;, plots.js
* Software: VS Code, Google Chrome

## Step 1: Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

![bar Chart](Images/hw01.png)

3. Create a bubble chart that displays each sample.

![Bubble Chart](Images/bubble_chart.png)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![hw](Images/hw03.png)

6. Update all of the plots any time that a new sample is selected.

![hw](Images/hw02.png)

## Challenge (Optional)

The following task is advanced and therefore optional.

* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.

![Weekly Washing Frequency Gauge](Images/gauge.png)

## Deployment

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.

