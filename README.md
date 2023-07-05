# Project Motivation
The scrapping script was done as part of Govtech's data arcade tournament, where members of singapore government agencies form a team of up to 3 people to take part. <br>
The tournament have a few categories, this webscrapping script was made for the data visualization and data storytelling category.

# How to use the Scripts

1. (optional) use the script scrap_company_names to scrap the name of all companies and put them into a csv. Note that this is a very long and tedious process given Indeed.com's anti scrapping measures.
2. Alternatively, have a list of company names in a csv that you want to scrap and run them with scrap_top_companies. Remember to change the name of the csv being read to company_names to your csv file.
3. run clean_scrapped_data, changing the file name in the scripts to your filenames. Then, manually correct unclean data if required. 

# Example of scrapped dataset
processed_company_review_data.csv - the dataset that was scrapped from indeed after undergoing data cleaning