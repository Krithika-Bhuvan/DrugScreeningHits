# Drug Screening Hits

## What is HTS data ?

Cell lines are created from patients for the advantage many drugs can be tested on these cell lines in the lab (in-vitro).  Drug response data in the form of EC50 values can be obtained for each for multiple doses which allows us to see which drugs a patient cell line is sensitive to 

This R Shiny app - DrugScreeningHits 
* Allows user to set a drug response value cut off that determines if a cell line is sensitive or not
* Lists the drugs that are sensitive 
* Allows to input one or more HTS files (i.e. more than one patient HTS data)
Shows drugs at are sensitive in “intersection” of files
Shows drugs at are sensitive in “union” of files


### Front page screenshot 

<img width="716" alt="image" src="https://user-images.githubusercontent.com/1800604/231880860-0f099fba-9ffe-4aa1-8204-f5aa09c6bc86.png">


### After input data is uploaded

<img width="744" alt="image" src="https://user-images.githubusercontent.com/1800604/231880878-d86aa848-7d1b-422c-842d-e4ba14bec71b.png">

### Link to shiny app

Link: https://krithikab.shinyapps.io/cdgnet_devel/

### Input data format
Input data must be csv or excel with the following column names
* Vendor Catalog
* Final EC50


