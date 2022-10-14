# Background

This working paper compares different delineations
https://www.jchs.harvard.edu/sites/default/files/Harvard_JCHS_Airgood-Obrycki_Rieger_Defining_Suburbs.pdf, which highlights the "census-convenient" definition in Kneebone & Nadeau (2015) as the best option for a quick nation-wide dataset
https://www.brookings.edu/wp-content/uploads/2016/06/1103_poverty_kneebone_nadeau_berube.pdf

However, this repository contains a simplified implementation of the Bureau of Justice definition centered more around weighted housing unit density (more accurate than population density) https://bjs.ojp.gov/content/pub/pdf/cusrancvs.pdf


# Data sources:

## Housing data

US Census's American Community Survey

Run the marked Jupyter cell to download a full dataset containing every state

# PDB

Planning Database (PDB) from US Census

PDB found here:
https://www.census.gov/topics/research/guidance/planning-databases.2021.html#list-tab-ZQ6WSS2CQ43P3UIVQ7
Name: './data_inputs/pdb.csv'

# Zip code lookup file

From US Department of Housing and Urban Development (HUD)

Zip &rightarrow; Census tract found here:
https://www.huduser.gov/portal/datasets/usps_crosswalk.html

Name: './data_inputs/zip_lookup.xlsx'
