## Local Election Data From Rajasthan

We scrape the [Rajasthan SEC site with gram panchayat results for 2020--2022](https://sec.rajasthan.gov.in/grampanchayatdetails.aspx). 

For scripts, see [here](scripts/). 

### Data

The PDFs + data posted at: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/6YPB5C

Data on contesting sarpanch, statistics for nomination, Winner Sarpanch (which includes a link to the pdf that we want to save with id = id of the candidate), and Ward winning panch.

From the main page, we get: 

```Election Type, Election Duration, District, Panchayat Samiti, Gram Panchayat```

From the contesting sarpanch tab, we get:

```
Sr. No., Name of Gram Panchayat, Category of Gram Panchayat, Contesting Candidate Serial No., Name of Contesting Candidate, Father/Husband of Contesting Candidate, Gender, Marital Status, Category of Candidate, Education Status, Contesting Candidate Occupation, Age, Total Value of Capital Assets (Land-Building-Jewelry), Children Before 27 11 1995, Children on or after 28 11 1995, mobile no., email address
```

From the winner sarpanch, we get:

```
Elected unopposed, total electorate votes, total polled votes, rejected votes, total valid votes, poll %, winner candidate name, pledge (pdf_file_name), vote secure by winner, runnerup candidate name, vote secure by runnerup, total number of nota count, tendered votes
```

For ward winning panch, we get all the columns and rows and the same for statistics for nomination
