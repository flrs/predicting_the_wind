# Predicting the Wind: Data Science in Wind Resource Assessment

2020-03-11, [PyData San Diego Meetup](https://www.meetup.com/PyData-San-Diego/)

## Contents

### Main Presentation: Predicting the Wind: Data Science in Wind Resource Assessment
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=presentation.ipynb) *(recommended start)* – [presentation.ipynb](./presentation.ipynb) 

*Update 2020-03-15: Now includes information about how to estimate turbine power output with long-term wind estimates.*

Presentation about data science in wind resource assessment. The presentation is about the fictitious scenario of 
building a wind farm on the hills around the AI incubator [The Sandbox San Diego](https://www.thesandbox.ai/). It 
explains how the wind can be measured and how the measurement can be used together with climate models and ground 
station data to generate a long-term estimate of the wind. Subsequently, the presentation shows how to use that estimate
 to predict wind turbine power output. Finally, the presentation puts the output of the fictitious wind farm into the
 broader context of the California power grid.
 
From a data science perspective, the presentation touches on data exploration, modeling and validation, and clarifies
 where domain knowledge of wind and fluid dynamics can help improve the wind estimate.

The presentation uses the following tool stack:
 - [Jupyter Notebook](https://jupyter.org/) as a basis 
 - [RISE Jupyter extension](https://rise.readthedocs.io/) for presenting the notebook 
 - [hide_code extension](https://github.com/kirbs-/hide_code) for hiding some (long-ish) code to build maps 
 - [Folium](https://python-visualization.github.io/folium/) to display maps
 - [SciPy's](https://www.scipy.org/scipylib/index.html) orthogonal distance regression
 - [scikit-learn's](https://scikit-learn.org) RandomForestRegressor
 - [brightwind](https://github.com/brightwind-dev/brightwind) to support wind resource assessment tasks

### Additional Content: Download and Pre-Process ASOS Data
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=data_acquisition%2Fdownload_and_preprocess_asos_data.ipynb) – [download_and_preprocess_asos_data.ipynb](./data_acquisition/download_and_preprocess_asos_data.ipynb)

A demonstration about how to download and preprocess meteorological data from ASOS measurement stations with Python 
in a Jupyter notebook.

### Additional Content: Synthesizing a (Mock) Wind Speed Time Series
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=data_acquisition%2Fsynthesizing_a_wind_speed_time_series.ipynb) – [synthesizing_a_wind_speed_time_series.ipynb](./data_acquisition/synthesizing_a_wind_speed_time_series.ipynb)

A Jupyter notebook that deals with how to come up with an artificial met mast time series when you only have some 
reference data and not a lot of time.