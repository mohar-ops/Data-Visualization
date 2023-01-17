# Data-Visualization
Coursework projects compiled

Dataset for Data Viz1:  ESSO - Indian National Centre for Ocean Information Services (INCOIS LAS) (An Autonomous Body under the Ministry of Earth Sciences, Govt. of India)
The dataset consists of 5 folders, each for different variables, namely, sea surface salinity (SSS), sea surface temperature (SST), sea surface height anomaly (SSHA), meridional current, and zonal current, during the period December 2003 – December 2005. The datasets are at a 5-day interval, thus giving 147 timesteps. Each of the folders also has a screenshot of the web page giving latitude-longitude ranges of each variable. The datasets for SSS, SST, and SSHA have data for 187 longitudes ranging in [29.8892W, 119.8237W], and 188 latitudes ranging in [29.7511S, 29.7511N]. Thus, each data file for a time-stamp has 187*188=35156 scalar values. The zonal and meridional current values can be treated as a single 2-dimensional vector field, where, zonal current speed (east-to-west speed, along latitude) can be assumed to be a u- (or x-) component, and meridional current speed (north-to-south speed, along longitude), as v- (or y-) component. The datasets for current values have data for 181 longitudes ranging in [30W, 120W], and 189 latitudes ranging in [30.0005S, 30.0005N]. Thus, each data file for a time-stamp has 181*189=37209 scalar values in each file. 

Dataset for Data Viz3 and Data Viz4: Dataset of students enrolled in courses at MIT and Harvard. It is composed of de-identified data from the first year (Academic Year 2013: Fall 2012, Spring 2013, and Summer 2013) of HarvardX courses on the edX platform along with related documentation. These data are aggregate records, and each record represents one individual's activity in one edX course.

Data Viz 1: Visualization Techniques:
Contour Fill (contourf)
Colormap (pcolor)
Quiver (quiver) 
The contour fill and colormap are used for scalar values and the quiver plot is used for vector values. 

Vector field plots: The meridional and zonal currents form the vector field visualizations
Scalar field plots: The Sea Surface Salinity, Sea Surface Temperature AND SSH Anomaly form the scalar field visualizations

Data Viz 2:In this assignment we have visualized scalar fields of: Salinity and Potential Temperature
and vector fields of: Zonal and Meridional currents

For Scalar fields: We use Isosurface and Surface from plotly.graph objects to generate isosurfaces and volume slices respectively. The contourf() function from matplotlib is used to generate additional depth profiles.

For Vector fields: We use the quiver() function to generate the plots.

For the scalar fields, we have 3 different kinds of visualizations:
Isosurface:  depth has been clipped till 50 meters to observe the data closer to the surface for both salinity and potential temperature. Perceptually uniform sequential colormap is chosen. 
 Observation : temperature in the ocean decreases with increasing depth.


Data Viz 3:Visualization of the given tabular data and remodeling it as a tree and a network k to find underlying patterns or communities formed.

Data Viz 4: A Tableau visualization of the dataset. To design a set of visualization tasks, implement a workflow with a feedback loop and data analytics along with visualization, and build a data story of the analysis of the dataset selected by the team. Our main aim is to effectively visualize the above data as a matrix and find the underlying patterns or clusters formed

Datasets are uploaded in the dataset folder.
The Google Drive links for the zipped code, output and demo videos have also been uploaded.

Data Viz 1: https://drive.google.com/file/d/1GCmSh6DHPBRlXckc-Nu4eIyw5gWvbemg/view?usp=share_link

Data Viz 2: https://drive.google.com/file/d/1DLw0eyh0AW4lsJkbS-nFCGnLEGJoDuUN/view?usp=share_link

Data Viz 3: https://drive.google.com/file/d/1_B0gjumyurrx_ne4Um5ZGj_FP1kxISPj/view?usp=share_link

Data Viz 4: https://drive.google.com/file/d/1P6i7tXN9MhKnAmZLfF7wef368RMkF4eS/view?usp=share_link


