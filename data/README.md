## Data

A selection of data used and obtained in this work are stored here. The details are below:

### Table 1
The .CSV version of Table 1 in the paper. Contains the core results.

### Scripts
`get_surface_data.ipynb` collects surface rotation rates from Vizier.

`get_data.ipynb` collects the LEGACY and Kages results from Vizier.

### Data Files

I used a very geeky naming convention based on [Brandon Sanderson's Mistborn series](https://www.brandonsanderson.com/the-mistborn-saga-the-original-trilogy/). The metals (and data) come in pairs: one with data from the literature, and then another containing the same information supplemented by values obtained in this work.

`malatium` (literature) + `atium` (this work): stellar parameters such as temperature, metallicity, and asteroseismic properties measured in this work. Table 1 is constructed from this file.

`copper` (literature) + `bronze` (this work): measured oscillation frequencies, line widths and mode heights.

The other two contain "a-priori" estimations of the hyperparameters for the asymptotic relation (`cadmium`) and the distribution of mode line widths (`bendalloy`) based on fits to literature data for stars where these were available.

the **tracks** folder contains stellar evolutionary tracks shown in Figure 1 of the paper.