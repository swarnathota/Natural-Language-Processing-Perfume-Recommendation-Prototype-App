# Perfume recommendation app

## Project description

Everybody likes perfume but very few of us know or understand ingredients in the perfume. My project makes it easier to find perfume for those who needs a perfume but doesn’t know which one to buy. For data collection I chose perfume description for ingredients of the perfume and reviews to extract when the user using the perfume such as occasion sports or date night or Christmas eve or everyday wear or seasons like summer or winter.

## Work flow 

#### Data collection

**.** For this project I collected data from the FranrenceX.com by web scraping using Selenium and BeautifulSoup

**.** Each perfume description and reviews are scraped and clubbed to into one text document per perfume.

**.** Details of Perfume such as rating, brand and name of the perfume is scraped.

**.** Each perfume text document and details made into a data frame.

####**Text processing and topic modeling**

**.** Spaces, extra tails, special characters, capitals and digits were removed from the text.

**.** Text is subjected to TF-IDF, to know how important the term to the document, and NMF for dimensionality reduction.

####  Results

**.** By measuring cosine similarity this model can return perfumes related to the string provided.

**.** Flask app is launched via Jupyter notebook to test the model.

## Where we can use 

**.** **Collaborative filtering** - makes predictions of what might interest a person based on the taste of many other users such as amazon and prime.

**.** **Content based filtering** - make recommendation based on key-word search of the items by the user 

**.** **Demographic recommendation** - users are grouped based on attributes and recommendations are made to the demographic profiles.

**.** **Hybrid** - Combination any of the above methods (Netfix uses this approach)

