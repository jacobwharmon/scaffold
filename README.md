## Example of project organization and workflow

### Directories
* Scripts
  - 0_collection
    * this is for scraping or downloading
  - 1_cleaning
  - 2_summary
    * ie detailed summary statistics, anything strange, outliers, etc
  - 3_analysis
    * regression, ML, etc
  - 4_tables_figures
* Data
  - 0_raw
    * this is where the freshly scraped or downloaded data should go. 
    * virtually no cleaning, anybody's scrape or download should match this
  - 1_temp
    * intermediate data cleaning steps
  - 2_clean
    * these are the inputs for summary, analysis, and tables_figures scripts
* Docs
  - words
  - tables
  - figures
* Notes
  - yyyymmdd.txt naming format. Maybe subfolders necessary?
