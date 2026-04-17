This README.txt file was generated on 2026-02-08 by Sena Isik


--------------------
GENERAL INFORMATION
--------------------


1. Title of Dataset: Assessment of Road Salt Impact on Native and Non-native Plant Species


2. Author Information
	A. Principal Investigator(s) Contact Information:
		Names: Sena Isik, Laura Vallejo Rubiano, Lucas Lang & Courtney Chan
		Institution: Simon Fraser University, Department of Environmental Science
		Email: dirtsafebc@gmail.com

3. Questions: For any questions about the dataset please email send an email to dirtsafebc@gmail.com


4. Program: Department of Environmental Science


5. Data steward: Environmental Science Students, Simon Fraser University, 8888 University Drive, Burnaby, BC, Canada, V5A 1S6


6. Date of data collection: 2026-02-27 to 2026-03-17


7. Geographic location of data collection:

Location	Stream name	x coordinates	y coordinates
Burnaby	        Stoney Creek	49.26578	-122.90169
Burnaby	        Eagle Creek	49.25167	-122.94000
Port Moody	Noons Creek	49.28394	-122.83339
Coquitlam	Hoy Creek	49.28722	-122.79714
Port Moody	Mossom Creek	49.30044	-122.86775
West Vancouver	Rodgers Creek	49.35222	-123.19083
	
All field sites are in British Columbia, Canada.


8. Information about funding sources that supported the collection of the data:

The following field equipment was borrowed from SFU:

	Hanna Instruments HI 98129 Waterproof pH/Conductivity/TDS Tester

	1 x 1 m field quadrat

	Field measuring tape


---------------------------
SHARING/ACCESS INFORMATION
---------------------------


1. Licenses/restrictions placed on the data:

These data are available under a CC BY 4.0 license
https://creativecommons.org/licenses/by/4.0/


2. Links to publications that cite or use the data: No external publications currently cite or use this dataset.


3. Links/relationships to ancillary data sets or software packages:

The dataset is associated with the Water Quality Statistics file, which contains aggregated descriptive statistics derived from the raw Field Site Measurements Data. Data processing, visualization, and statistical analyses were conducted using Excel, JMP, and R. No additional external datasets were used.


5. Was data derived from another source? No


6. Recommended citation for this dataset:

Sena Isik, Laura Vallejo Rubiano, Lucas Lang, and Courtney Chan (2026). Assessment of Road Salt Impact on Native and Non-native Plant Species. Simon Fraser University Summit Research Repository. Generated 2026-02-08. Accessed [YYYY-MM-DD] from https://summit.sfu.ca


---------------------
DATA & FILE OVERVIEW
---------------------


1. File List

   A. Filename: Field Survey Site Measurements.csv
      Short description: This file contains water quality measurements, including pH, water temperature, total dissolved solids (TDS), and electrical conductivity (EC), along with site information such as arrival and departure times, site coordinates, and field observations.

   B. Filename: Field Survey Plant Count Data.csv
      Short description: This file contains plant survey data for each stream site, including counts and percent cover of native, invasive, introduced, and unidentified species recorded within quadrats.

   C. Filename: Water Quality Full Statistical Analysis.jmpprj
      Short description: This file contains JMP statistical outputs from Pearson correlation analyses of water quality parameters, including graphs and filtered DFO PSEC Community Stream Monitoring (CoSMo) data.

   D. Filename: Field Survey R Script.txt
      Short description: Contains R codes for biodiversity analyses (Chao1 richness, Simpson’s diversity, evenness), species accumulation and k-dominance curves, linear models of vegetation cover vs. EC, and associated statistical results (e.g., p-values and figures).
   
   E. Filename: Species Richness Per Quadrat.csv
      Short description: Species richness per quadrat data were calculated in Excel and exported as a CSV file, containing species identities for each quadrat across all streams and corresponding richness values to assess biodiversity patterns and compare species composition and spatial variation within and between sites.

   F. Filename: Average Plant Cover Per Quadrat.csv
      Short description: Average plant cover per quadrat was calculated in Excel and exported as a CSV file, summarizing vegetation cover at 0 m, 2.5 m, and 5 m quadrat positions for each stream to assess spatial variation in plant cover within and between sites.

   G. Filename: Non parametric Tests for Field Survey.jmpprj
      Short description: This file contains JMP statistical outputs from non-parametric tests (Kruskal-Wallist and Wilcoxon tests) to test the differences in total vegetation cover across EC stream classifications and to assess relationships between EC levels and percent cover for each plant category.

   H. Filename: EVSC_species_abundance.csv
      Short description: Stream-level species cover data were uploaded to R, summarizing mean relative cover of individual plant species across all sampling points for each stream site.

   I. Filename: EVSC_species_per_quadrat.csv
      Short description: Species-level percent cover data for each quadrat were uploaded to R, with each column representing an individual plant species categorized by origin (native, invasive, introduced, or unidentified) for use in community composition and diversity analyses.
  
   J. Filename: EVSC_enviro_factors.csv
      Short description: Includes vegetation cover data (total_invasive, total_introduced, total_native, total_unidentified, total_cover) for each stream site were uploaded to R for analysis.

   K. Filename: Streams Biodiversity Index.csv
      Short description: Stream-level biodiversity metrics were calculated in Excel, including Chao1 species richness estimates, variance in Chao1, total percent cover, and Simpson’s diversity index to compare richness and diversity across streams with different electrical conductivity classifications.


2. Relationship between files, if important:

Plant count and water quality measurements were collected simultaneously at each stream site. The Field Survey Site Measurements file contains environmental and water quality data, while the Field Survey Plant Count file contains vegetation data for the same sites and sampling events. All analysis was conducted in R and Excel.

Raw data were reformatted into species-level, quadrat-level, and stream-level datasets to calculate relative abundance, percent cover, Simpson’s diversity, and Chao1 richness. These outputs were then linked with environmental variables, including conductivity classification and sampling distance, to compare vegetation patterns across sites.


3. Additional related data collected that was not included in the current data package:

Field observations for each site, including channel morphology, substrate type, flow characteristics, and notable environmental features, were recorded in a field notebook and later described in the capstone project report but are not included in the submitted data files.


4. Are there multiple versions of the dataset? No


---------------------------
METHODOLOGICAL INFORMATION
---------------------------


1. Description of methods used for collection/generation of data:

Field surveys were conducted at six stream sites classified as high or low conductivity based on short-term acute chloride exposure thresholds. Plant cover was measured using 1 x 1 m quadrats along transects, with percent cover calculated as the number of plants per cell per quadrat divided by 100 total cells. Species were classified as native, introduced, invasive, or unidentified.

Reference: Roberts-Pichette, P., & Gillespie, L. (1999). Terrestrial vegetation biodiversity monitoring protocols. Ecological Monitoring and Assessment Network (EMAN), Biodiversity Science Board of Canada. https://publications.gc.ca/collections/collection_2014/ec/En36-2-9-1999-eng.pdf

Invasive species identification was assisted using https://bcinvasives.ca/take-action/identify/

Water quality parameters (pH, conductivity, TDS, and temperature) were measured using a Hanna Instruments HI 98129 Waterproof pH/Conductivity/TDS Tester (https://www.amazon.ca/Hanna-Instruments-Waterproof-Conductivity-Tester/dp/B002ZG8L58)


2. Methods for processing the data:

Data was collected on a field notebook and phone and was later entered into the excel spreadsheet.


3. Instrument- or software-specific information needed to interpret the data:

Probe used for water quality measurements:

	Hanna Instruments HI 98129 Waterproof pH/Conductivity/TDS Tester

Software used for statistical summary and analysis:

	JMP Student Edition 19
	R (version 4.5.3)

Other software/apps used:

	Excel (Microsoft 365) for data entry and organization
	Seek by iNaturalist (latest version) for plant species identification

Link to DFO PSEC Community Stream Monitoring (CoSMo):

	https://pacificdatastream.ca/explore/#/dataset/4c8d3691-99e5-4fa9-ad09-da077baa37c5/?tab=statistics


4. Standards and calibration information, if appropriate:

The Hanna Instruments HI 98129 probe was calibrated with distilled water before and after measurements at each stream site.


5. Environmental/experimental conditions:

Weather varied during data collection, including sun, rain, and snow. Stream conditions also varied by site, with differences in flow, substrate, shading, and surrounding vegetation, which were recorded in field notes. Data represent field conditions at the time of sampling, which may not reflect seasonal or long-term variability. Sites were selected based on proximity to roads, forest cover variation, accessibility, and distance from major roadways. Conductivity measurements were used as a proxy for road salt exposure. Average daily air temperature (°C) and total daily precipitation (mm) were added from https://climate.weather.gc.ca/. Stream classification was based on conductivity values relative to the 2000 µS/cm acute chloride exposure threshold.


6. Describe any quality-assurance procedures performed on the data:

Distances from the riparian zone were measured with a field tape to ensure consistent quadrat placement along transects, following Roberts-Pichette & Gillespie (1999). Plant identifications were verified in the field with Seek by iNaturalist and cross-checked through the BC Invasive Species Council website to ensure accuracy (https://bcinvasives.ca/take-action/identify/). Data were entered into Excel and checked for consistency and completeness before analysis in JMP and R.


7. People involved with sample collection, processing, analysis and/or submission:

All principal investigators were involved in sample collection. Sena led water quality measurements, and analysis. Lucas and Laura contributed to data entry 
with laura analyzing and processing the data. Courtney assisted with plant identification and verification.


-------------------------------
DATA-SPECIFIC INFORMATION FOR:
-------------------------------


A. Filename: Field Survey Site Measurements.csv

	1. Number of variables: 31

	2. Number of cases/rows: 166
	
	3. Definitions:
	
		survey date	     			Date on which the respective location was surveyed
		arrival time         			Time of arrival to field site
		departure time 	     			Time of departure from field site
		stream ID	     			Identifier variable used to join Field Survey Measurements and Field Survey Counts
		station name	     			Name of the closest available CoSMo monitoring station in the surveyed stream
		stream name	     			Name of the surveyed stream
		x & y coordinates    			X and Y coordinates of the closest available CoSMo monitoring station in the surveyed stream
		ph 1, 2 & 3	     			Individual pH recordings with which average pH was calculated at the time of survey
		avg ph	             			Average pH of the surveyed reach
		water temperature 1, 2 & 3 (°C)		Individual water temperature recordings with which average  water temperature was calculated at the time of survey
		average daily air temperature (°C)	Average temperature of the surveyed reach
		tds 1, 2 & 3 (ppm)   			Individual TDS readings with which average stream TDS was calculated at the time of survey
		avg tds (ppm)	    			Average TDS of the surveyed reach
		ec 1, 2 & 3 (μS/cm)  			Individual electrical conductivity readings with which average stream eC was calculated at the time of survey
		avg ec (μS/cm) 	     			Average electrical conductivity of the surveyed reach, in uS/cm
		approximate width (m) 			Visually approximated width of the surveyed reach
		approximate height (cm) 		Visually approximated height of the surveyed reach
		comments				Comments on stream condition and relevant findings


B. Filename: Field Survey Plant Count.csv

	1. Number of variables: 44

	2. Number of cases/rows: 7920

	3. Codes:

		n		   			Native
		i	           			Introduced
		v	           			Invasive
		u	           			Unidentified
	
	4. Definitions:
		total native         			Total percent cover for native species
		total introduced     			Total percent cover for introduced but not invasive species
		total invasive       			Total percent cover for introduced invasive species
		total unidentified   			Total percent cover for unidentified species


-----------------
ACKNOWLEDGEMENTS
-----------------

The investigators acknowledge Professor Jeremy Venditti and teaching assistant Chloe Ross for their help on acquiring field equipment.
