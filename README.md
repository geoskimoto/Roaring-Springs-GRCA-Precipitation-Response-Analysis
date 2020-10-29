# Precipitation Response Analysis of Roaring Springs, Grand Canyon, AZ

## Objectives:

•	Use pulses of water as a tracer much the same way as a traditional flourescent dye to determine temporal variation in response times in discharge and water temperature at Roaring Springs, Grand Canyon.

•	Pulses of water include monsoon precipitation events that flash through the groundwater system and snowmelt events that are triggered by warming surface temperatures.  Both events can be observed in output signal hydrograph data.

•	Determine response times of these pulses via cross-correlation through the North Kaibab Plateau to Roaring Springs.

•	See if methodology can be used to also determine travel paths of pulses through major secondary porosity conduits. PRISM dataset consists of daily precip and surface temp values measured at 145 locations/pixels on the Kaibab Plateau. Run cross correlations using for loop for each location with the hydrograph data to see which locations correlate the best. Exploratory and doesn't provide great resolution, but might be able to inform future dye traces.

•	Perform descriptive analysis on hydrograph data checking for stationarity, autocorrelation, and partial autocorrelation.

•	Perform causality analysis to see what input signals (precipitation, surface temperature on Kaibab Plateau, snow depth and SWE, EVT, and soil moisture) granger cause the output signals (discharge and water temperature at RS).  Eventually, build Bayesian Causal Network to get a better handle on what variables control spring response. 

•	Conduct Precipitation Reponse Modelling via a SARIMAX model. Maybe limited by data or models maybe too complicated or over-fit. If so, perform linear systems analysis or lumped parameter models. Purpose is to simulate response of spring and to determine conduit-to-fracture/matrix coupling and what variables play a role in the response of the spring.

![Work Flow of Analysis](/workflow.png)
