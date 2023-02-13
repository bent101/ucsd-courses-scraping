# Scraping the UCSD course catalog

The UCSD course catalog is littered with inconsistency under the hood. This notebook scrapes all 6,888 courses across 82 pages, cleans the data, and puts it in a JSON file for manual fixing. It then goes through the descriptions of the courses and turns mentions of major codes/other courses into HTML links. I plan to use this data to make a new and improved course catalog.
