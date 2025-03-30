## Overview 
This project automates the extraction of Crown Court data from AWS Athena and exports it to an S3 location in Excel format. Using a Python notebook, the workflow queries Athena, processes and formats the data into a structured Excel document, and seamlessly uploads it to S3. The solution ensures efficient data retrieval, transformation, and storage for further analysis or reporting.

## Content 
- **Python Notebook**
   - cout_caseload_extract.iypnb
- **Four .yml Files:** 
   - crown_court_rpt__receipts_disposals_open_quarterly.yml
   - crown_court_rpt__receipts_disposals_open_annual.yml
   - crown_court_rpt__trial_receipts_disposals_open_quarterly.yml
   - crown_court_rpt__trial_receipts_disposals_open_annual.yml
- **Sample Extract**
   -  crown_court_extract.xlxs
- **s3 Location**
   -  s3://alpha-fotest/
