# Code Description

`code/01_clean_data.R`
- read raw data from `raw_data/` folder
- save clean data in `cleaned_data/` folder

`code/02_descriptive_table.R`
- read clean data from `cleaned_data/` folder
- save table 1 in `outputs/` folder

`code/03_mosaic_plot.R`
- read clean data from `cleaned_data/` folder
- save mosaic plot in `outputs/` folder

`code/04_render_report.R`
- render `report.Rmd` 
- save compiled report in main project directory

`report.Rmd`
- read data, tables, and figure from respective locations
- display results for production report