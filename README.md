# Project Brief
Data needed on student accomodation, from rent prices, to size.  Many hours spent manually copying the data down into an excel file to analyse.  Would be great if it could be automated.  

Project Steps:
* Create blank pandas df to be populated
* Scrape Data:
    * Request HTML from Student Accommodation (https://www.mystudenthalls.com/) site
    * Scrape for Property, Owner/Operator, Address, Link URL
    * Scrape for 1 x Type, Rent (p/w vs pcm), weeks
    * Scrape for N x (Type, Rent (p/w vs pcm), weeks)
    * Scrape for Area (sqm vs sqft)
* Populate Pandas DF
* Calculate
    * Rent PA
    * £psf PA
* Create form to choose uni and returns csv file with data on.

<video width="320" height="240" controls>
  <source src="media/manual_data_collection.mov" type="video/mp4">
</video>