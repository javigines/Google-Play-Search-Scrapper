# Google Play Search Scrapper
Retrieve some useful data from a google play search term


# Requirements
- Python 3
- Requests (Pip module)

# Config
Configuration is inside scrapper.py file.

![](/readme_files/config_example.png)

    - manual_data_scrap (True/False)
    Define if the data scrap from the search have to be done from the source code paste in the             manual_data_scrap file or the search should be done with the above config terms.

    - search_word
    Term to be search in Google Play Store

    - country_code
    Country code of of the country in which the search musdt be done.

# Result

![](/readme_files/result_example.png)

The data scrapper shows:
- Number of different app authors in the search
- Number of different app in the search
- Rating average of the apps in the search

For each author it returns:
- The apps with their rating and their name

(With the correct print it could returns the author and the apps links, but I don't needed and I don't print it, but is in the final data map)

