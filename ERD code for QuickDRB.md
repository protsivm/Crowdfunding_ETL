ERD code for QuickDRB


# Modify this code to update the DB schema diagram.
# To reset the sample schema, replace everything with
# two dots ('..' - without quotes).

campaign
-
cf_id	
contact_id	
company_name	
description	
goal	
pledged	
outcome	
backers_count	
country	
currency	
launched_date	
end_date	
category_id	
subcategory_id

contacts
-
contact_id FK 
first_name
last_name
email

