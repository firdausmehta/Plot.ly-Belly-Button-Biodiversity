## Background
I have created an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogues the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

The dashboard can be accessed from the link: https://firdausmehta.github.io/Belly-Button-Biodiversity-Plot.ly/

## The dashboard will accomplish the following:
1. Reading the samples.json using D3 Library.
2. A horizontal bar chart with a dropdown menu to display the top 10 OTUs found in the individual selected.

    a. Use sample_values for bar chart values.

    b. Use otu_ids for bar chart labels.

    c. Use otu_labels as hovertext for the chart.

3. Create a bubble chart that displays each sample.

    a. Use otu_ids for x values.

    b.Use sample_values for y values.

    c. Use sample_values for marker size.

    d. Use otu_ids for marker colors.

    e. Use otu_labels for text values.

4. Displaying sample metadata like demographic info for individual.
5. Displaying each key-value pair from the metatdata JSON object on the page.
6. Ability to update the plots anytime a new smaple is selected.

<img width="595" alt="hw02" src="https://user-images.githubusercontent.com/80393628/131209878-efdcac29-4311-426d-8988-8d47ea4544b8.png">
