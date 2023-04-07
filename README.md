# SI485
# Gender Stereotypes in e-commerce systems

*Executive Summary*

The main goal of this current research in collaboration with Boise State University is to draw attention to the presence of gender stereotypes in non-US-based e-commerce systems and its impact on the experience and behaviors of users searching for children’s toys.
 Ultimately, the project’s minimum viable product is a well-formatted dataset created from scraping two UK-based e-commerce systems. This dataset will demonstrate how search results are impacted by specific, gendered queries. The two e-commerce systems analyzed will be Amazon UK and Argos to provide international data to expand the already existing research.
PIReT will compare the Amazon UK and Argos’ query suggestions and search results data to existing U.S.-based data to further analyze the presence of gender stereotypes. Our notebooks document the queries from the international sites, and have clear documentation of the code to ensure the process can be replicated for other websites in the future.


# Analysis
*SIGIR_QS_az.ipynb*: code analyzing the data collected in the Amazon UK notebooks (in the code folder) for gender associations.

*SIGIR_QS_argosuk.ipynb*: code analyzing the data collected in the Argos notebooks for gender associations.

# predoc_info
*all_items.txt*: list of toys used as search inputs for scraping.

*predoc_stereotyped_items.csv*: items from all_items.txt sorted by stereotypical gender associations with a column of toys for boy, girl, and neutral.

*predoc_toys_w_gender_labels.csv*: toys from all_items.txt labelled with stereotypical gender associations with one column containing the gender label (boy, girl, or neutral) and another column containing the toy.

*selenium.ipynb*: code to install selenium


# Code
***Amazon UK***</br>

*az_uk_search_results.ipynb*: Code putting different queries into Amazon UK's search engine, scraping the search results page for product titles and product codes.

*scraping_azuk_UMSI.ipynb*: Code putting different queries into the Amazon UK search bar, scraping the resulting query suggestions.

***Argos***</br>

*argos_search_results.ipynb*: Code putting different queries into the Argos search engine, scraping the search results page for product titles and product codes.

*scraping_argos_UMSI.ipynb*: Code putting different queries into the Argos search bar, scraping the resulting query suggestions.


# Results

***Amazon UK***</br>

*az_uk_query_suggestions.csv*: resulting csv file containing data obtained from scraping Amazon UK's IR system's query suggestions.

*az_uk_search_results.csv*: resulting csv file containing data obtained from scraping Amazon UK's search results for each item.

***Argos***</br>

*argos_query_suggestions.csv*: resulting csv file containing data obtained from scraping Argos's IR system's query suggestions.

*argos_search_results.csv*: resulting csv file containing data obtained from scraping Argos's search results for each item.
