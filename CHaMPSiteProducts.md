# CHaMP Site Products

Successful completion of the CHaMP protocol at a site leads to production of the following Products.  See **[Where Can I find Products?](CM_SiteProductLocations.md)** for data access information. 

### **[1. Metrics:](https://github.com/SouthForkResearch/CHaMP_Metrics/wiki)**
Visit-specific summaries of physical site features at the time of sampling.  Tabular metrics are generated by the following engines:

* auxiliary
* topographic
* topographic-auxiliary   

Final metrics are accessible from the [CHaMP Workbench](http://workbench.northarrowresearch.com) or CHaMPmonitoring.org (Metrics tab). QA metrics are also available from these locations if a User has the appropriate Permissions.  

### [2. Site Properties]([https://riverscapes.github.io/CHaMPAutomation/engines/SiteProps.html](https://www.google.com/url?q=https%3A%2F%2Friverscapes.github.io%2FCHaMPAutomation%2Fengines%2FSiteProps.html&sa=D&sntz=1&usg=AFQjCNE9b4jDBhEyhPn2Ym4g_CsFqOjHbg)):
Topographic control networks for each site packaged for scouting map generation, crew evaluation and use, and upload to total stations. Files are available from the Site Documents tab of champmonitoring.org.  

### **3. Topographic Survey Files (Visit-specific)**: 
Raw survey input and post-processed topographic output files files packaged into a [hierarchical folder structure](http://champtools.northarrowresearch.com/9_technical_reference/project/) by the [TopoToolbar](http://champtools.northarrowresearch.com).  
Files are available from the Field Data Upload Utility tool of champmonitoring.org (TopoData.zip).  

### **4. CAD Files (Visit-specific):**  
Post-processed topographic survey files in a CAD-friendly file format. These files are a specific subset of topographic survey products. Files are available from the Visit Documents page of champmonitoring.org (CADExport.zip)  

### [5. Hydraulic Model](https://southforkresearch.github.io/Hydraulic-Modeling/): 
A Delft-3D hydraulic model is used to produce hydraulic model estimates of depth and velocity throughout a site.  Models are run for the discharge at the time of sampling (Surveyed results) and each site has one model using a spring, high flow (Modeled results).   There are separate products of hydraulic model input files, surveyed result files, and modeled result files for each Visit and are available from the Visit Documents tab of champmonitoring.org.   

There are 4 types of files affiliated with hydraulic models that are available on the Visit Documents tab:

* *_Hydraulic Model Inputs_*: Topographic files prepped for input to the Delft Hydraulic Model.
* *_Hydraulic Model Result_*: Model result files. Products that begin with "S" are for surveyed flows (summer low flows at time of topographic survey).  Result products that begin with "M" are for modeled flows (usually spring high flows at the time of topographic survey).  
* *[_Hydraulic Model GIS files_](https://southforkresearch.github.io/CHaMP_Metrics/docs/hydro_export.html)*: Model result files transformed into GIS-friendly shapefiles and rasters.  
* *[_High Flow_* Hydraulic model products](https://southforkresearch.github.io/Hydraulic-Modeling/):  The Hydraulic model was run at a 'spring' (April) high flow Q for one Visit per site.  See the "M" visits in the Inventory (below).

[CHaMP Hydraulic Models Inventory](https://docs.google.com/spreadsheets/d/1W9kVoatVREc4Wru7jgB3a6Si69gX71MwQ2pfcWZ-UW4/edit?usp=sharing)  

### **6. Substrate Rasters:** 
A stream-bed roughness raster of a specified grain size (a percentile of a grain size distribution curve) based on ocular substrate size estimates within the bankfull channel.  Rasters will be available from the Visit Documents tab in January 2018).  

### **7. QRF-based habitat capacity:**  
A quantile regression forest model has been developed to estimate carrying capacity from paired fish and habitat sampling, including a number of CHaMP metrics. Versions of QRF capacity estimates exist for Chinook summer parr, Chinook redds, juvenile steelhead and steelhead redds. These estimates can be found through Riverscapes.

### **8. Fish-Habitat Model Products:** 
A set of juvenile and spawner habitat model products ready produced using a preset suite of fish-habitat relationships.  There are several fish-habitat models produced by the [Habitat Model](habitat.northarrowresearch.com) software: 

* **habitat suitability index (HSI)-based capacity:** Depth, velocity and substrate rasters are used in habitat suitability curves to produce estimates of habitat capacity. Products available from the Visit Documents tab of champmonitoring.org.  
* **fuzzy inference (FIS) habitat capacity version 1:** Depth, velocity and substrate inputs are used in a fuzzy inference system to produce estimates of habitat capacity.  Products available from the Visit Documents tab of champmonitoring.org.  
* **fuzzy inference (FIS) habitat capacity version 2:** In 2017, the fuzzy inference habitat capacity models were updated to include structural elements and aspects of fish cover.  Products available from the Visit Documents tab of champmonitoring.org in early 2018 for the subset of CHaMP sites where this model has been run.  
* [**NREI**](http://isemp.org/projects/nrei/): Net Rate Energy Intake models use the velocity and depth rasters from hydraulic models, temperature, and drifting invertebrate biomass information to estimate of energetic-based habitat capacity for the site.  Products available from the Visit Documents tab of champmonitoring.org in early 2018 for 2011-2016 Visits.  

### **9. 2016 GCD Products:**

### **[10. Globally Available Attributes](GloballyAvailableAttributes.md)**

### Retired file types
Site Geodatabases and Survey Geodatabases were retired after the 2016 field season.  These files utilized the proprietary ESRI 'geodatabase' file format and have been replaced by the 'Site Properties' and 'Topographic File' products. They are available upon request. 

[Return to QA Home](QAMain.md)

