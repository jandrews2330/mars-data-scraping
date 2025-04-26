# mars-data-scraping
Overview of the project: 
Part 1: Scrape Titles and Preview Text from Mars News
- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
- The titles and preview text of the news articles were scraped and extracted.
- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.
Part 2: Scrape and Analyze Mars Weather Data
- The HTML table was extracted into a Pandas DataFrame.
- The data was analyzed to answer the following questions:
    - How many months exist on Mars?
    Answer: 12
    - How many Martian days' worth of data are there?
    Answer: 1,867
The data was analyzed to answer the following questions, and a data visualization was created to support each answer:
    - Which month, on average, has the lowest temperature? The highest?
    Answer: Month 3 (lowest); Month 8 (highest)
    - Which month, on average, has the lowest atmospheric pressure? The highest?
    Answer: Month 6 (lowest); Month 9 (highest)
    - How many terrestrial days exist in a Martian year?
    Answer: Inspecting the chart above, it looks like it takes about 650 days to complete temperature cycle. This is corroborated by a google search which verifies a Martian year is approximately 687 Earth days. 
The DataFrame was exported into a CSV file.

Data extraction and analysis was prepared using prior class examples and with the assistance of Xpert Learning Assistance. 