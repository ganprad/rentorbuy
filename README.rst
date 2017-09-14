rentorbuy
=========
A Project that uses Zillow research data on Quandl, Prophet for time series forecasting, Geopy for geocoding, Altair for vega-lite charts and Folium for creating an interactive map.

The markers display forecasts of PHIV(Percentage of Homes Increasing in Value) for different zipcodes in the Chicago area. 
The data is available on Quandl and PHIV is one among many metrics available from Zillow Research Data.
The forecasts were generated using Prophet, it's intuitive interface made it a 
convenient choice to get started with time-series analysis. Altair made it possible to generate vega-lite
charts depicting forecasts. These vega-lite charts were then embedded into an interactive map
using Folium.

.. image:: folium_vega.gif

`Live example <https://bl.ocks.org/ganprad/b6fec5a6080d3274a96f96866db49749>`__

Install Anaconda(https://docs.anaconda.com/anaconda/install/) and setup environment using:

  - ``conda create -n myenv python=3.4``
  - ``pip install -r requirements.txt``

Tools:
---------------------

For accessing Quandl data an api key is needed:
https://blog.quandl.com/getting-started-with-the-quandl-api

Prophet:
https://facebookincubator.github.io/prophet/

Geopy:
https://github.com/geopy/geopy

Altair and Vega-lite:
https://altair-viz.github.io/index.html
https://vega.github.io/vega-lite/

Folium:
https://github.com/python-visualization/folium

Inspiration:
-----------
https://www.dataquest.io/blog/data-science-portfolio-project/



