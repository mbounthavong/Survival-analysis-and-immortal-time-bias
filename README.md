# Survival-analysis-and-immortal-time-bias
This GitHub page contains materials for a [tutorial on RPubs](https://rpubs.com/mbounthavong/survival_immortal_time_stata) that I created on how to handle immortal time bias in survival analysis using Stata. 

I also included the [R Markdown code](https://github.com/mbounthavong/Survival-analysis-and-immortal-time-bias/blob/main/R%20Markdown%20code/immortal_bias_stata.Rmd) that was used to create the RPubs tutorial.

I used the [paper](https://www.acpjournals.org/doi/10.7326/0003-4819-145-5-200609050-00009?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed) by Sylvestre and colleauges as a motivating example. They re-analyzed results from a 2001 [paper](https://www.acpjournals.org/doi/10.7326/0003-4819-134-10-200105150-00009?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed) by Redelmeier and Singh. 

## Background
In 2001, the Annals of Internal Medicine published a paper by Relemeier and Singh that reported that actors/actresses who won an Academy Award had higher survival rates compared to controls. However, there was a concern that immortaly time bias could have given the Academy Award winners a surivival advantage. Sylvestre and colleagues re-analyzed the data and reported that there was a strong possiblity that this immortal time bias did give the winners an advantage over the controls. 

## Motivating example
Using data from the Sylvestre, et al study, I re-created the analyses using Stata. 

# References
Sylvestre MP, Huszti E, Hanley JA. Do OSCAR winners live longer than less successful peers? A reanalysis of the evidence. Ann Intern Med. 2006 Sep 5;145(5):361-3; discussion 392. doi: 10.7326/0003-4819-145-5-200609050-00009. PMID: 16954361.

Redelmeier DA, Singh SM. Survival in Academy Award-winning actors and actresses. Ann Intern Med. 2001 May 15;134(10):955-62. doi: 10.7326/0003-4819-134-10-200105150-00009. PMID: 11352696.


