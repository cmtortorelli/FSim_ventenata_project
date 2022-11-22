# FSim_ventenata_project: 
“Feeding the fire: annual grass invasion facilitates modeled fire spread across Inland Northwest forest-mosaic landscapes” 
Tortorelli et al. 2022, Ecosphere

FSim simulated fire comparisons between ventenata invaded and uninvaded landscapes, Blue Mountains Ecoregion, OR, USA

### Metadata
Supporting data are available from Open Science Framework DOI 10.17605/OSF.IO/9AWTS 

**AllData_cleaned_2022.RData**
Point grid at 120m resolution, column descriptions below:
*>foa10_ = FSim output for invaded scenario (120 m resolution)*
*>foa12_ = FSim output for uninvaded scenario (120m resolution)*
•	X1: unique identifier
•	OID: coordinates
•	X: X coordinate
•	Y: Y coordinate
•	foa10BP: BP from invaded simulation (FSim output at 120 m resolution)
•	us_140frg: fire regime group from LANDFIRE 1.4.0 (resampled to 120m resolution from 30m resolution)
•	us_200vcc: Landfire existing vegetation type from LANDFIRE 2.0.0 (resampled to 120m resolution from 30m resolution)
•	foa10CFL: conditional flame length from invaded simulation (FSim output at 120 m resolution)
•	foa10MI: mean intensity from invaded simulation  (FSim output at 120 m resolution)
•	SAF_SRM: SAF SRM vegetation classification from LANDFIRE (resampled to 120m resolution from 30m resolution)
•	reclass: Reclassified LANDFIRE vegetation class with some lumping described in Appendix S1
•	alteredFM2: 1 = fuel model was altered to reflect invasion, NA = fuel model was not altered from uninvaded simulation
•	PRE_FM40: Scott & Burgan 40 fuel model classification from LANDFIRE for the uninvaded simulation (resampled to 120m resolution from 30m resolution)
•	Post_FM40: Scott & Burgan 40 fuel model classification from LANDFIRE for the invaded simulation (resampled to 120m resolution from 30m resolution)
•	EucDist2: Euclidean distance to nearest invaded cell (calculated in ArcGIS)
•	Foa12MI: mean intensity from uninvaded simulation (FSim output at 120 m resolution)
•	Foa12BP: burn probability from uninvaded simulation (FSim output at 120 m resolution)
•	Foa12CFL: conditional flame length for uninvaded simulation (FSim output at 120 m resolution)
•	difMI: difference in mean intensity between invaded and uninvaded simulation
•	difBP: difference in burn probability between invaded and uninvaded simulation
•	foa10FIL1 through foa10FIL6: Flame length exceedance probabilities for the 6 flame length categories for the invaded simulation (FSim output at 120 m resolution)
•	foa12FIL1 through foa12FIL6: Flame length exceedance probabilities for the 6 flame length categories for the uninvaded simulation (FSim output at 120 m resolution)
•	foa10FIL8: cumulative probability of exceeding 8 ft flame lengths for invaded simulation
•	foa12FIL8: cumulative probability of exceeding 8 ft flame lengths for uninvaded simulation
•	difFIL8: difference between invaded and uninvaded simulations of flame lengths exceeding 8 ft
•	foa10FILg4: cumulative probability of exceeding 4 ft flame lengths for invaded simulation
•	foa12FILg4: cumulative probability of exceeding 4 ft flame lengths for uninvaded simulation
•	difFILg4: difference between invaded and uninvaded simulations of flame lengths exceeding 4 ft


**foa10_XFirePerimsIntersect.csv
& foa12_XFirePerimsIntersect.csv**
Descriptions for columns below:
•	Shape_Area – size of intersecting polygon between vegetation types for each fire
•	AffectedCode – vegetation type that fire spread into
•	IgnitionCode- vegetation type that ignition occurred in
•	FIRENO – unique fire identifier that corresponds with ignition locations 
