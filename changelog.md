# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [0.1] - 2019-09-01
### Fixed
- [Excel exporter] Used gspread to update data. Much easier and faster

### Ideas
- [Excel exproter] Group by month and sum rows. Probably MONTH + pivot table can hepl 

## [0.1] - 2019-08-25
### Fixed
- [Excel exporter] Fixed the problem of adding new categories

### Ideas
- [Excel exproter] Save in .xls and convert to spreedsheets https://pypi.org/project/gspread-pandas/ 
- [Visualization] Use Graphana

## [0.1] - 2019-08-04
### Fixed
- [Excel exporter] Fixed the `last_columns` export to the Excel file
- [Excel exporter] Chnaged the categories update

## Ideas
- [Excel exporter] A new categories need to be a smoothly without re-running existed rows. Probably `insert_row` of `gspread` can help
- [Excel exporter] d3.js for plotting graphs. 

