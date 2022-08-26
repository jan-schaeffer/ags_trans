# Transition Matrix for Community Identification Numbers (Amtliche Gemeindeschlüssel, AGS)

This notebook creates a dataset of German municipalities AGSs over the years 1990-2020. Since there were several administrative reforms, creating consistent time-series/panels using the AGS as index is often not possible. 

The notebook requires the files:

- ref-gemeinden-1990-2000.xlsx
- ref-gemeinden-2000-2010.xlsx
- ref-gemeinden-2010-2020.xlsx

which are available from the BBSR at: https://www.bbsr.bund.de/BBSR/DE/forschung/raumbeobachtung/umstiegsschluessel/umstiegsschluessel.html 

Please note that the layout of the excel sheets was changed after 2015 and to rerun the script one has to manually change the headers from, e.g., 'Gemeinden 31.12.2017' to 'Kennziffer'. 

In the /data folder I provide a full dataset of all Municipalities (ags_transition.csv) as well as only those municipalities, where the AGS has changed over the years (ags_changes.csv).

Happy panelling!