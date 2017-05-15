# ARMIS
ARMIS stands for *Automated Recall Monitoring Information System*.

ARMIS utilizes several techniques to extract information from RSS feeds and press release websites. There is a disparity between the data sharing capabilities of the FDA versus USDA, such as the existence of Application Programming Interfaces (APIs). The complexities presented in the ARMIS project come from how existing statutes and rules are written and implemented. Mostly, existing rules assume a human will examine and find the pertinent information in a given press release. Therefore, the program is meant to mimic this process rather than find the most efficient means of data extraction. 

For example, openFDA (open.fda.gov) has an API wherein a program can readily query the FDA database for new information on recalls. However, the API is technically non-validated data and cannot be used by States to track recalls. There are many reasons for this. Principally, prodromal and nonreported recalls are accessible through the API, but there is no way to verify whether it is a bona fide recall except through analysis of the PR webpages. The openFDA API is used to increase fidelity of the natural language processing of ARMIS. The USDA does not have this capability and will not for the foreseeable future. 

To start ARMIS, download
