Rent or Buy?
=========== 
An *example workflow* using real estate data, creating forecasts and embedding them in an interactive map.
This could be a starting point of a deeper analysis.

Map description:
---------------
- The markers display forecasts of PHIV(Percentage of Homes Increasing in Value) for different zipcodes in the Chicago area. PHIV is one among many metrics available from Zillow Research Data on Quandl.
- The forecasts were generated using Prophet, it's intuitive interface make it a convenient choice to do time-series analysis. 
- Altair makes it possible to generate vega-lite charts depicting forecasts. 
- These vega-lite charts are then embedded into an interactive map using Folium. 

Please have a look at the notebook for code used to generate the map.

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



