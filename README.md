# hbwater_cameratrap_pheno
building a pipeline for processing HB Water aquatic camera trap photos for machine learning, with hopes to support further efforts to produce models from similar datasets.


## Project Steps 
1. image data re-organization 
2. ROI  
3. project file organization, structure, and primary host - GDrive? Server?
4. created inverted masked images
5. classify pixels in image using image annotator 
6. run random forest model
7. create data product: markdown
8. create data product: application


## Current Objectives
Tasks | People | Step
------- | -------- | --------
~~continue debugging the GDrive image copy/rename/organization scripts~~| BG, HS | **1**
~~figure out how to show mask on consecutive images (clicking thru all the images from a particular watershed year)~~ | HO, BG | **2**
allow user to, while clicking through images, stop and create a new mask associated with the date of that image  | HO, BG, HS | **2**
organize the GitHub repo (remove uneeded scripts and standardize naming conventions, etc.)   | HS | **3**
figure out our file hosting options: server, google drive, local files, etc.   | AT, WS | **3**


## Future Objectives
Tasks | People | Step
------- | -------- | --------
create walkthrough with example files as both proof-of-concept for our data pipeline, and as a walkthrough for future users | XX | **7**
export Jupyter notebook to *.py* files  | XX | **8**


## Notes
While the above steps are roughly in order, we will be working on certain aspects of the project throughout, such as:
  - Keeping all code well-documented and clean
  - Creating Jupyter notebooks for each script with embedded markdown/html that explains each step of the script


## Progress
- Figured out how to click through image files with mask applied
- Working on redrawing ROI and applying new mask to remaining images
- Working on file naming conventions/organizing GitHub


## Repo Structure

README.md

data
- derived_data
- raw_data

scripts
- 01-filename
- 02-filename
- helpers.py
- old-scripts
- etc.

dep
- roipoly.py
- etc.


