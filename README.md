# Predicting the Wind: Data Science in Wind Resource Assessment

2020-03-11, [PyData San Diego Meetup](https://www.meetup.com/PyData-San-Diego/)

## Contents

### Presentation
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=presentation.ipynb) *(recommended)* – [presentation.ipynb](./presentation.ipynb) 

*If the presentation on Binder does not start automatically, click this button in the toolbar: <img src="./images/presentation_start_button.png" width="22" height="16">*

Presentation about data science in wind resource assessment. The presentation is about the fictitious scenario of 
building a wind farm on the hills around the AI incubator [The Sandbox San Diego](https://www.thesandbox.ai/). It 
explains how the wind can be measured and how these measurements can be used together with climate models and ground 
station data to generate a long-term estimate of the wind. From a data science perspective, the presentation clarifies 
where domain knowledge of wind and fluid dynamics can help improve the estimate.

The presentation is built in an interactive [Jupyter Notebook](https://jupyter.org/) that uses the 
[RISE Jupyter extension](https://rise.readthedocs.io/) and the 
[hide_code extension](https://github.com/kirbs-/hide_code). It uses 
[Folium](https://python-visualization.github.io/folium/) to display maps, 
[SciPy's](https://www.scipy.org/scipylib/index.html) orthogonal distance regression, and 
[scikit-learn's](https://scikit-learn.org) RandomForestRegressor. In addition, the presentation shows how the 
[brightwind](https://github.com/brightwind-dev/brightwind) Python module helps to analyze wind patterns.

### Download and Pre-Process ASOS Data
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=data_acquisition%2Fdownload_and_preprocess_asos_data.ipynb) – [download_and_preprocess_asos_data.ipynb](./data_acquisition/download_and_preprocess_asos_data.ipynb)

A demonstration about how to download and preprocess meteorological data from ASOS measurement stations with Python 
in a Jupyter notebook.

### Synthesizing a (Mock) Wind Speed Time Series
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/flrs/predicting_the_wind/master?filepath=data_acquisition%2Fsynthesizing_a_wind_speed_time_series.ipynb) – [synthesizing_a_wind_speed_time_series.ipynb](./data_acquisition/synthesizing_a_wind_speed_time_series.ipynb)

A Jupyter notebook that deals with how to come up with an artificial met mast time series when you only have some 
reference data and not a lot of time.