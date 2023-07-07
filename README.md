# Various python cookbooks
___

Example notebooks for various domain-specific problems

## Authors
[Rob Junod](https://github.com/rajunod)

## Runing the Notebooks

The following notebooks can be ran on Google Colab:

- NOAA_climo_percentiles.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajunod/cookbooks_various/blob/main/NOAA_climo_percentiles.ipynb)

### Running on Google Colab

Click the Google Colab button above.

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:
1. Clone the `https://github.com/rajunod/cookbooks_various` repository:
   ``` bash
   git clone https://github.com/rajunod/cookbooks_various.git
   ```
1. Move into the `cookbooks_various` directory. Pick the the.yml that corresponds to the notebook of interest.
   ```bash
   conda env create -f $NAME_OF_NOTEBOOK$.yml
   conda activate $NAME_OF_NOTEBOOK$
   ```
1. Start up JupyterLab
   ```bash
   jupyter lab
   ```
   
