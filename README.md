# Project Mitti

### About Mitti:

**What**: Mitti (which means "soil" in Hindi) is a machine learning-powered, agricultural information platform that was born out of my research on digital agriculture at MIT.  

**Why**: Mitti is designed to enable smallholder farmers in developing countries, specifically India, overcome information barriers that lead to unsustainable fertilizer usage by providing timely, actionable nutrient management advice.

**How**: Mitti integrates disparate public and private datasets (such as satellite imagery, soil testing data, and weather forecasts) to provide a customized, comprehensive nutrient recommendations.

### About this Repo:

The purpose of this repository is to give a sneak-peek of progress on Mitti. Instead of sharing code, I will provide an overview of the methodology.

### Data:
**[This section will be updated periodically. Last update: Mar 18, 2019]**

Status: I am currently building the soil test module of Mitti for one specific geography - Latur district in the state of Maharashtra, India. For this, I am using data from the

The data folder currently contains two datasets:
1. GeoJson file showing all villages in Latur district compiled by the Pune DataMeet project. Citation: https://github.com/knickhill/datameet-pune.github.io
2. Soil health card scheme (an Indian government program) for Ahmedpur taluk downloadable from https://soilhealth.dac.gov.in/ as a csv file

### Dependencies:

The statical geospatial analysis was carried out in Python. All the dependencies have been added to the specs.txt file

You can replicate the environment by running the following code in the terminal.
```
conda create --name myenv --file spec-file.txt
```

### Results:
**[This section will be updated periodically. Last update: Mar 18, 2019]**
