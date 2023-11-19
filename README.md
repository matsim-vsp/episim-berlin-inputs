# Episim-Berlin-Inputs

Release according to data protection provision "Open Data Agreement of 8.12.2020" between Senozon Deutschland and the VSP department at the TU Berlin.

EPISIM-MODEL OF THE VSP DEPARTMENT AT THE TU BERLIN:
## The usage and download of the following open available files are only allowed for an epidemiological simulation of Berlin.
## Do not use the files for other simulations.

The open availbale model includes a 25 percent sample. The code for running the simulation is also open available under: https://github.com/matsim-org/matsim-episim
More information you find on our website: https://covid-sim.info/ . This is the same version that is available [here](https://doi.org/10.14279/depositonce-11495.2).
If you have questions, please contact covid19@vsp.tu-berlin.de 

Files:
be_2020-week_snz_entirePopulation_emptyPlans_withDistricts_25pt_split.xml.gz:
	Population including all persons having activities in one of the events files. The person attributes are homeId, homeCoordinates, age, district of home.
	The coordinates are in grid accuracy of 500m.

be_2020-week_snz_episim_events_sa_25pt_split.xml.gz
be_2020-week_snz_episim_events_s_25pt_split.xml.gz
be_2020-week_snz_episim_events_wt_25pt_split.xml.gz
	The episim events files for a weekday, Saturday and Sunday. The events files are filtered for the only necessary types of events (actend, actstart, PersonEntersVehicle, PersonLeavesVehicle).

be_2020-vehicles.xml.gz
	File includes a mapping of vehiclesIds to the vehilce type.

be_2020-facilities_assigned_simplified_grid.xml.gz
	Including the facilities used in the events files. The coordinates are in grid accuracy of 500m.
	
be_2020-mobility_data.csv
	Daily mobility data for Berlin for the simulated period.

sha256sums:
c8c0fa24f183a7ba399f52d7dd94cb590a9628311c5c4fc3fb53e3b48894aa95  be_2020-week_snz_entirePopulation_emptyPlans_withDistricts_25pt_split_grid.xml.gz
aea3c4b8fb64a5a4d8320042c6a1b412a43245072db0eb8bb54e7a44e9bdf106  be_2020-week_snz_episim_events_sa_25pt_split.xml.gz
12c0037ff8a7dde26c383de7c6a68254742b053058f143d52c449ad4d9d20259  be_2020-week_snz_episim_events_so_25pt_split.xml.gz
664f9d166a0fd33bdbaf2a2ad7fe1c75795ffd73cd4180e314b398cc2b4c98d8  be_2020-week_snz_episim_events_wt_25pt_split.xml.gz
8e0209721b5bfb8596f653a998572ead6356676e3d539b4f74475e8dd2fa5e44  de_2020-vehicles.xml.gz
bbb2d032a1f7d493053dc5d77eed7b0f23b4319f30a276f19fbf1e016691e23c  facilities_assigned_simplified_grid.xml.gz
