# Plotly-Biodiversity_Analysis
University of Oregon: Data Analytics Boot Camp repository for homework assignment number 12.

### Plot.ly Homework - Belly Button Biodiversity

### Step 1: Plotly
1) Use the D3 library to read in samples.json.

2) Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
* Use sample_values as the values for the bar chart.
* Use otu_ids as the labels for the bar chart.
* Use otu_labels as the hovertext for the chart.

3) Create a bubble chart that displays each sample.
* Use otu_ids for the x values.
* Use sample_values for the y values.
* Use sample_values for the marker size.
* Use otu_ids for the marker colors.
* Use otu_labels for the text values.

4) Display the sample metadata, i.e., an individual's demographic information.

5) Display each key-value pair from the metadata JSON object somewhere on the page.

6) Update all of the plots any time that a new sample is selected.
* Additionally, you are welcome to create any layout that you would like for your dashboard.

### Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.
* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.
* You will need to modify the example gauge code to account for values ranging from 0 through 9.
* Update the chart whenever a new sample is selected.

### Deployment
* Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.
* https://mathewqpmiller.github.io/Plotly-Biodiversity_Analysis/
* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### Hint
* Use console.log inside of your JavaScript code to see what your data looks like at each step.
* Refer to the Plotly.js documentation when building the plots.
