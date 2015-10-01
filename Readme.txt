To update the BAGIS-P setting files, please copy the files to their associated folders under the path defined by the BAGIS environment variable.
The BAGIS settings folder (i.e., BAGIS) should sit under the paht. For example, if the BAGIS path is C:\BAGIS, then the settings file folder structure looks like:

C:\BAGIS\BAGIS
C:\BAGIS\BAGIS\profiles
C:\BAGIS\BAGIS\methods

See the list below for the files contained in each folder.

==================
BAGIS\
==================
Readme.txt - this file
parameter_descriptions.txt - BAGIS-P uses this file to display parameter descrition texts when exporting the calculated parameters.

==================
BAGIS\profiles
==================
BAGIS_Parameters.csv - default template file for exporting parameters to eWSF PRMS
Profile_eWSF_PRMS.xml - the parameter profile that defines the collection of parameters used by eWSF PRMS
Profile_eWSF_PRMS_NWCC.xml - the parameter profile that defines the collection of parameters used by NWCC eWSF PRMS. The adjust tmax and tmin values are set to 0.

==================
BAGIS\methods
==================
bagis_method_building_blocks.tbx - ArcGIS toolbox containg BAGIS-P building block Modelbuilder models 
bagis_p_climate_methods.tbx - ArcGIS toolbox containg BAGIS-P climate Modelbuilder models 
bagis_p_generic_methods.tbx - ArcGIS toolbox containg BAGIS-P generic Modelbuilder models 
bagis_p_soil_methods.tbx - ArcGIS toolbox containg BAGIS-P soil Modelbuilder models 
bagis_p_vegetation_methods.tbx - ArcGIS toolbox containg BAGIS-P vegetation Modelbuilder models 
bagis_topographic_methods.tbx - ArcGIS toolbox containg BAGIS-P topographic Modelbuilder models 
bagis_parameters.txt - BAGIS-P uses this file to check if PRMS required parameters are available for the BAGIS-P export function.
*.xml files - a collection of xml files defining the individual BAGIS-P methods
