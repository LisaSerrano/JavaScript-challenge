 # Belly Button Biodiversity Interactive Dashboard

## Background
In this assignment, an interactive dashboard is built to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals insights into the microbial species present in human navels.

## Instructions
To complete this assignment, follow these steps:

1. Use the D3 library to read in the samples.json dataset.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 operational taxonomic units (OTUs) found in each individual's sample.
    - Use sample_values as the values for the bar chart.
    - Use otu_ids as the labels for the bar chart.
    - Use otu_labels as the hovertext for the chart.
3. Create a bubble chart to display each sample:
    - Use otu_ids for the x values.
    - Use sample_values for the y values.
    - Use sample_values for the marker size.
    - Use otu_ids for the marker colors.
    - Use otu_labels for the text values.
4. Display the sample metadata, i.e., an individual's demographic information.
5. Update all the plots when a new sample is selected.
6. Deploy the app to a free static page hosting service, such as GitHub Pages.

### Advanced Challenge Assignment (Optional)
Optionally, adapt the Gauge Chart to plot the weekly washing frequency of the individual:
- Modify the gauge chart code to account for values ranging from 0 through 9.
- Update the chart whenever a new sample is selected.
