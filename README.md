# Glycomics R Processing Pipeline
This repository contains the R-scripts used for glycomics and glycoproteomics data processing for the publication with DOI:.

After using [MassyTools](https://github.com/Tarskin/MassyTools/releases/tag/v2.1.6) and conversion of the output into an Excel file (.xlsx) you can use the data in the following scripts.
The order to run the scripts is:
- MassyTools to R-Readable Data Conversion script. Used version is v11.
- Check Blanks. Used version is v1.1.
- Glycan Data Curation. Used version is v4.0.1.
- Glycosylation_trait_scripter. Used version is v1.2.3.
- Glycan Data Check After Curation. Used version is v4.0.0.

In the top part of these scripts is a block called 'settings'. You only have to adapt the filenames in these settings when you recreated the data from the original files. These are indicated between hooked brackets <>.
