This folder contains a test snapshot of a CorsixTH game based on the each release version of CorsixTH.

A guide on what parameters create the test are also included below. You will need a copy of Theme Hospital to open these files.

----------------------------
*Version 1.0 - June 2025*\
For layout guides see `layout_p1.png` and `layout_p4.png` and `plots.png`

**Building a test save for release**\
In order to keep saves as close to being set up as similarly as possible the following steps details how to make a test save from a release. 
This save isn't designed to replicate a perfect hospital and should simulate some level of management issues.

Notes: Enable debug and 'build while paused' in the configuration file before starting, if not already. Also make sure 'Allow blocking off areas' and 'Wage requests' is disabled/denied.

1. Launch the final release version of CorsixTH for the save you want to make
2. Start a new campaign with normal difficulty (doctor)
3. On loading into Level 1, use the debug menu to jump to Level 5 instead. Pause the game
4. Open the town map and buy the bottom right tile (plot 4). Then increase heating by 1 notch (+)
5. Open the hiring screen, hire:\
  a. the first, second, and last doctor\
  b. the first nurse\
  c. the first handyman\
  d. the last receptionist
6. Build the following without additional windows (if staff get in the way, temporarily unpause then pause again once clear)\
  a. A reception desk in Plot 1 (your starting plot) near the north entrance\
  b. GP office in bottom left of Plot 1 (8 tiles wide, 4 tiles tall)\
  c. Toilets opposite the GP office (8 tiles wide, 4 tiles tall), total 3 loos, 2 sinks\
  d. General diagnosis in Plot 1 left of the Reception Desk (5 tiles wide, 6 tiles tall)\
  e. Psychiatrist in Plot 1 between the Toilets and General Diagnosis on the left wall (5 tiles wide, 6 tiles long)\
  f. Pharmacy in Plot 1 between the Psychiatrist and Toilets (4 tiles wide, 4 tiles long)\
  g. Operating Theatre in Plot 1 right of the Reception Desk (6 tiles wide, 7 tiles long)\
  h. Staff Room in Plot 1 in the bottom right corner (5 tiles wide, 6 tiles long), total 2 sofas, 1 TV, 1 pool table, 1 video game\
  i. Inflation left of the Staff Room (5 tiles wide, 5 tiles tall)\
  e. Ward in Plot 4 in the top right, (6 tiles wide, 8 tiles tall), total 3 beds, 1 desk\
  j. Training in Plot 4 in the bottom (10 tiles wide, 5 tiles tall), total 5 chairs, 1 bookcase, 1 skeleton\
  k. Research between the Ward and Training (6 wide, 6 tall), 1 desk only
7. Add additional objects to each room from the furnish corridors tool:\
  a. 2 radiators in the ward, 1 radiator in every other room (12 radiators)\
  b. 1 raditor next to the entrance door of every room (11 radiators)\
  c. 1 bin in the Ward, GP Office, and Inflator rooms (3 bins)\
  d. 1 bin near the Reception Desk\
  e. 1 plant in every room (11 plants)\
  f. 3 plants in the entrance corridor of Plot 1\
  g. 1 fire extinguisher in Inflator\
  h. 2 drinks machines in Plot 1, 1 in Plot 4 (3 drinks machines)\
  i. 20 benches total in Plot 1 (on walls of patient rooms)\
  j. 4 benches total in Plot 4 (outside Ward)
9. Place your consultant researcher in the Research room
10. Place your consultant surgeon and the two least qualified hired staff in the training room until both are qualified surgeons (or becomes a consultant, whicher is sooner).\
Remove all staff from room once achieved (do not move during training to the operating theatre)
11. Open the hospital and run the game until September 1st. For decision making:\
  a. VIP Visits - always accept\
  b. Emergencies - always accept except for ones requiring surgery (operating theatre)\
  c. Epidemics - always declare epidemic\
  d. Earthquakes - repair machinery in warning quake\
  e. Patient diagnoses - risk cure if confidence is >= 75% otherwise send home in all other cases.\
  f. Salary raises - always accept\
  g. Do not manually move staff\
  12. Save game on September 1st labelled `xx test save` where xx is the release number e.g. 0.68.0
