# nosql-challenge
Here's a summary of our findings from the NoSQL challenge:

Database Setup
## Database Created: uk_food
## Collection Loaded: establishments
Successfully imported data from establishments.json into MongoDB.
Updates Made to the Database
## New Restaurant Added: "Penang Flavours" was added to the database.
## Business Type ID Updated: Found and assigned the correct BusinessTypeID for "Restaurant/Cafe/Canteen."
## Dover Establishments Removed: All establishments under "Dover" were deleted, reducing clutter in the dataset.
## Data Type Corrections:
Converted latitude and longitude fields from strings to decimal numbers.
Converted RatingValue from strings to integers for consistent querying.
Exploratory Analysis Findings
## Hygiene Score of 20:
Found 41 establishments with a hygiene score of 20.
Sample document displayed for verification.
## Establishments in London with RatingValue >= 4:
Identified 33 establishments meeting the criteria.
Sample document displayed for reference.
## Top 5 Establishments with RatingValue of 5:
Listed top 5 establishments, sorted by the lowest hygiene score, located near "Penang Flavours."
Ensured all results had a RatingValue of 5.
## Count of Establishments with Hygiene Score of 0:
Aggregated data revealed the top local authority areas with a hygiene score of 0.
Displayed the counts for the top 10 local authorities, helping to identify potential health risks.
## Conclusion
The analysis provided valuable insights into food hygiene ratings across various establishments, highlighting areas of concern and assisting the magazine in focusing their future articles effectively.
