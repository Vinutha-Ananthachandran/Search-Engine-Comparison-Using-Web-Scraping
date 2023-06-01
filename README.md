# Search-Engine-Comparison-Using-Web-Scraping
Dataset - 100QueriesSet2.txt
Google Reference - Google_Result2.json
----------------------------------------------------------------------------------------------------------------------------------------------------------
Result:
======
	1. Average Number of Overlaps - 2.22

	2. Average Overlap Percentage - 22.2

	3. Average Spearman Coefficient - -7.304928571

----------------------------------------------------------------------------------------------------------------------------------------------------------
Inference:
=========
	1. Average Overlap percentage for the given dataset is 22.2. Since we are using google dataset as the reference, we can indicate that this
	   overlap score means that the results returned from the Yahoo search engine are not identical to the baseline and that the relevance of search
	   hits(result) is of lower quality.
	
	2. Average Spearman Coefficient for the given dataset is -7.304928571. This negative value indicates that the 2 search engines being compared(Google
	   and Yahoo) are uncorrelated. This means the algorithms used by these 2 search engines emphasize or prioritze features differently while ranking 
         the document.
----------------------------------------------------------------------------------------------------------------------------------------------------------
Summary:
=======
	Based on the overlap percentage and the Spearman coefficient, we can conclude that Yahoo performs worse than Google when Google serves as the point 
	of reference.
