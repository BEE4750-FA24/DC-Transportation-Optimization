# DC-Transportation-Optimization
#BEE 4750 Final Group Project
Group 3: Maya Zamor, MacKenzie Fountain, Noah Hartman, Raashid Husain

### System Optimization of Air Pollutants from Vehicular Transportation

##### An overview of the system:
Our project will minimize an objective function that calculates the net carbon dioxide emissions produced by tailpipe emissions from various sources of transportation; internal combustion engines (ICEs), electric vehicles (EVs), and buses (see Figure 1 for control volume). The scope of this project aims to include the CO2 emissions from one city. During our preliminary meeting, our team discussed using Ithaca as a model. Decision variables include the number of electric vehicles, gas vehicles, and buses. Constraints include the city’s capacity of gas vehicles and buses, the city’s EV infrastructure capacity, and any emissions standards/thresholds set by the EPA and/or NYSDEC. We chose this topic since we were interested in the cross-section of transportation and air pollution as the shift to electric vehicles expands.

##### A rough idea of the experimental design/possible data sources/uncertainties:

For our model, we will source data for Ithaca due to the amount of data and research that has been conducted by previous students and research teams whose goals align with our group’s. Additional data that has not been collected or published that is necessary to conduct our research can be obtained with the use of various global positioning softwares such as ESRI and ArcGIS. This will help us produce routing maps to obtain distances traveled by buses to determine the amount of tailpipe CO2 emissions produced. Some uncertainties we will consider include unknown drastic population changes and sudden regulation changes affecting EV infrastructure.

##### A work plan including tasks for each group member to lead:
Raashid: overall writing and group coordination
Maya: bus transportation data collection, office hour coordination
MacKenzie: Internal group timeline creation and management
Noah: Data collection overview and method organization

Plans for group coordination:
All group meetings will be held over Zoom unless otherwise planned in-person. We will coordinate action items and progress via group text messages.




Figure 1: The control volume (CV) for our research will be the city of Ithaca. Specifically, we will create a bounding box on a map of the city of Ithaca, which will give us the length and width of this control volume. CO2 emissions due to aircraft flying over the city will not be incorporated in the model, so we can approximate a height of about five kilometers. There is no input or output to the control volume as we are focused only on transportation within the city. 
