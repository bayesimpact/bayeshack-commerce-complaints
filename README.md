# Bayes Hack 2016
### Department of Commerce Prompt #1

_How can data protect consumers from financial foul play?_

## Prompt

More than two years after the Consumer Financial Protection Bureau began collecting complaint data, the consumer complaint database is now a public repository of over 100,000 consumer complaints. It's a rich resource for CFPB analysts and financial institutions searching for emerging trens about consumer complaints relating to financial services products, including complaint justifications and responses or resolutions.

The CFPB forwards complaints to the appropriate company for a response, analyzes complaint data to provide regulatory oversight, enforces federal consumer financial laws, and writes better rules and regulations. Now the CFPB is exploring how this data can be transformed into smart tools to optimize internal processes, improve consumer complaints, or to focus scrutiny on shady practices.

## In this Repo

* `data/` - Cleaned and prepared data sources. NOTE - Not all data exists here -- see Resources section below.
   * `data-samples/` contains heavily downsampled versions of datasets, so you can poke around easily. They're in CSV, so Excel or Google Sheets should be able to load them too.
* `analysis/` - iPyton notebook files (which you can view right here on GitHub) loading the data and exploring a few things. Good to understand the datasets and get ideas for your project.

## Data Quirks

`data/commerce-consumer-complaints.csv`
* Consumer narratives aren’t tracked until mid 2015 sometime
* The “Company response to consumer” field is the one that tells you what the result of the complaint was.
   * The values for this field changed sometime in 2012, it seems
   * Prior, all complaints were marked either "Closed with relief" or "Closed without relief."
   * Sometime in 2012 changed to 3 options - "Closed with explanation", "Closed with monetary relief", or "Closed with non-monetary relief"

## Resources

* The Commerce Data Service offers a tutorial for merging the American Community Survey's public datasets with the Consumer Complaint Database to highlight areas of specific need within particular communities: ["Extending the ACS: Data-driven Outreach"](http://commercedataservice.github.io/tutorial_acs_rank/).
