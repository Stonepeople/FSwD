

# FINDING STORIES WITH DATA

Files accompanying [CIJ course](https://tcij.org/scheduled-training) Finding Stories with Data

**Module 1**

-   You will need [this file](https://github.com/Stonepeople/FSiD/blob/main/donations2019_2020_Exercise.xlsx) which
    contains exercises consolidating the skills taught in session 1.

-   [This](https://github.com/Stonepeople/FSiD/blob/main/Interviewing_data.pdf) is the short presentation

-   -   If you just want to read about pivot tables [this pdf](https://github.com/Stonepeople/FSiD/blob/main/PIVOT%20TABLES.pdf) is all you need

-   [Spreadsheets for journalists](https://github.com/Stonepeople/FSiD/blob/main/SPREADSHEETS%20FOR%20JOURNALISTS%20HANDOUT.pdf) is the
    handout I wrote for a one-day course covering everything we now do in the 4 online sessions of Finding Stories with Data

**Module 2**

-   This is the [presentation](https://github.com/Stonepeople/FSiD/blob/main/FindingData.pdf) on Finding Data used in module 2

-   [Follow the Money](https://github.com/Stonepeople/FSiD/blob/main/FollowTheMoney.pdf) is a set of links to help get you started if you're interested in financial stories

-   A fuller list of advanced operators the [Cheatsheet](https://github.com/Stonepeople/FSiD/blob/main/GoogleguideCheatSheet.pdf) is downloaded from [googleduide.com](http://www.googleguide.com/print/adv_op_ref.pdf). You may also want to read  this excellent [Guide to Google Dorking (another name for advanced searching)](https://exposingtheinvisible.org/guides/google-dorking/) to get a deeper insight into what we did, and how it can help your investigation. It also covers some important security issues. 

-   Links from the [Finding data presentation](https://github.com/Stonepeople/FSiD/blob/main/Links%20from%20FindingData.pdf)

The [Awesome Public Datasets repo](https://github.com/awesomedata/awesome-public-datasets) as the name suggests - is awesome!

-  a set of generally [useful links](https://github.com/Stonepeople/FSiD/blob/main/USEFUL%20LINKS%20TO%20DATA.pdf) to help get you started

These [tabs](https://www.one-tab.com/page/JkfVibrkRyuw8EeOIscRag) will take you to the information and sites in the main presentation

**Module 3 prep**

-   Before you attend to module 3 itself, we recommend you watch at least the first four videos:
-   . [ImportHTML](https://youtu.be/h3Nyld3wNzY) - converting a table from a web page to a spreadsheet, using Googlesheets. (At the moment, for reasons unknown, the parliament.uk site will not allow importhtml to work with the [Register of Interests of MPs' Secretaries and Research Assistants](https://www.parliament.uk/mps-lords-and-offices/standards-and-financial-interests/parliamentary-commissioner-for-standards/registers-of-interests/register-of-members-secretaries-and-research-assistants/). It still works with Excel, however. No idea what's blocking it!
-   [Clean with Open Refine](https://youtu.be/HCeH8QMHvmQ) - cleaning names in a dataset where slight differences make the computer see them as different entries
-   [Export your OpenRefine project](https://youtu.be/UWJIu0Ss4eU) How to convert your data back to Excel/Googlesheets after cleaning it in OpenRefine. The source table is this [Wikipedia page](https://en.wikipedia.org/wiki/List_of_MPs_elected_in_the_2019_United_Kingdom_general_election) if you want to follow the same steps
-   [Reconcile with Open Refine](https://youtu.be/3CV6rEn0stM) Matching names in a column in OpenRefine with company names on OpenCorporates.com. NB – to make use of the OpenCorporates reconciliation service you need to add this address to the reconciliation menu in OpenRefine https://opencorporates.com/reconcile (see 1.18” in this video). See [here](https://api.opencorporates.com/documentation/Reconciliation_API_documentation_v0.1.pdf) for documentation. OpenCorporates have recently added a security layer to the reconcilication feature: you now need to register your IP address in order for reconciliation to work on your PC. This doesn't take long, and costs nothing, but it will stop you experimenting with reconciliation based on this module. 

**Module 3**
-   To allow us more time to talk and try out some of the techniques you may need to use to prepare data for analysis, we ask you to watch these videos as preparation for session 3. Rather than spending a whole live session being bombarded with new information, you can come prepared, possibly having had a chance to try some of the techniques for yourself, or ready to ask questions and solve them in the session. 
-   [ImportHTML](https://youtu.be/h3Nyld3wNzY) - converting a table from a web page to a spreadsheet, using Googlesheets
-   [Clean with Open Refine](https://youtu.be/HCeH8QMHvmQ) - cleaning names in a dataset where slight differences make the computer see them as different entries
-   [Export your OpenRefine project](https://youtu.be/UWJIu0Ss4eU) How to convert your data back to Excel/Googlesheets after cleaning it in OpenRefine. The source table is this [Wikipedia page](https://en.wikipedia.org/wiki/List_of_MPs_elected_in_the_2019_United_Kingdom_general_election) if you want to follow the same steps
-   [Reconcile with Open Refine](https://youtu.be/3CV6rEn0stM) Matching names in a column in OpenRefine with company names on OpenCorporates.com. NB – to make use of the OpenCorporates reconciliation service you need to add this address to the reconciliation menu in OpenRefine https://opencorporates.com/reconcile (see 1.18” in this video). See [here](https://api.opencorporates.com/documentation/Reconciliation_API_documentation_v0.1.pdf) for documentation
-   [Convert tables](https://youtu.be/xZ_sPdJtOLo) in pdf files to csv spreadsheets with [Tabula](https://tabula.technology/) another excellent free program
-   Enhance one dataset by merging relevant data from another using the [Vlookup](https://youtu.be/NCBP8Z1x_RY) formula. 
-   [Clean names](https://youtu.be/tCET1qWOb3U) with OpenRefine - Remove honorifics such as “Mr”, “Mrs”, “Dr, while also creating a reproducible script to save time doing the same job on future occasions
-   [Power Query](https://youtu.be/9P6iyjPguok) A relatively new Excel feature which allows you to merge data without learning VLOOKUP. It also keeps a record of what you have done, so you can check or reproduce your work – eg when you use a later edition of the same data.

Practice material accompanying the videos
•	To practice “VLookup” you need to download a copy of [this worksheet](https://github.com/Stonepeople/FSiD/blob/main/MPs_donations_vlookup_exercise.xlsx) containing the two datasets.
•	If you want to practise cleaning the MPs names (removing titles etc) using OpenRefine as in the video "Cleaning names with OpenRefine", you will need to download a copy of [this dataset](https://github.com/Stonepeople/FSiD/blob/main/Donations_to_MPs.csv)
•	To get a copy of the company donation data demonstrated in the cleaning and reconciling videos (2nd and 4th on the list), open [this link](http://search.electoralcommission.org.uk/?currentPage=1&rows=10&sort=AcceptedDate&order=desc&tab=1&open=filter&et=pp&et=ppm&et=tp&et=perpar&et=rd&isIrishSourceYes=true&isIrishSourceNo=true&date=Reported&from&to&quarters=2021Q1234&quarters=2020Q1234&prePoll=false&postPoll=true&donorStatus=company&register=gb&register=ni&register=none&optCols=Register&optCols=CampaigningName&optCols=AccountingUnitsAsCentralParty&optCols=IsSponsorship&optCols=IsIrishSource&optCols=RegulatedDoneeType&optCols=CompanyRegistrationNumber&optCols=Postcode&optCols=NatureOfDonation&optCols=PurposeOfVisit&optCols=DonationAction&optCols=ReportedDate&optCols=IsReportedPrePoll&optCols=ReportingPeriodName&optCols=IsBequest&optCols=IsAggregation) in a new tab, and download a copy of the resulting file - using the [Export results] button.

•	To practice the Power Query demo with the data used in the [video](https://youtu.be/9P6iyjPguok) you will need to download copies of these two datasets:
– [donations to MPs](https://github.com/Stonepeople/FSiD/blob/main/Donations_to_MPs.csv) 
and
[list of MPs elected in 2019](https://github.com/Stonepeople/FSiD/blob/main/ListofMPs2019election.csv)

-   Although OpenRefine contains links to useful instructional videos, [this pdf](https://github.com/Stonepeople/FSiD/blob/main/OPEN%20REFINE%20STARTER%20NOTES_JS.pdf) is intended as a useful written guide to get you started

-   Reconciling lists using OpenRefine is covered in [this pdf](https://github.com/Stonepeople/FSiD/blob/main/Reconciling%20in%20OpenRefine.pdf)

-   [Scraping the web](https://github.com/Stonepeople/FSiD/blob/main/scraping%20the%20web.pdf) is an excellent tipsheet from [IRE](https://www.ire.org/) (it's well worth joining IRE. At around $70 a year it's worth  joining just for the library of tipsheets!)

**Module 4**

-   [Why visualise](https://github.com/Stonepeople/FSiD/blob/main/Why%20visualise%20CIJ.pdf) is the presentation used in module 4. 
-   There's a quick introduction to making graphics from spreadsheets in two parts [Part 1](https://youtu.be/CPG3tj2vZYg) takes you raw data to a graph, and introduces you to [Datawrapper](https://www.datawrapper.de/). [Part 2](https://youtu.be/n3cFrf4pQsc) takes a look at creating a graph from a pivot table. 
-   [This video](https://youtu.be/Qv-g9XhpOf0) looks at how to do the same thing with Googlesheets
-   There's a more detailed step-by-step guide to making a visualisation from an Excel pivot table [here](https://youtu.be/Pakq8_hauwI) and from googlesheets [here](https://youtu.be/q4TxXLBpxa8)
-   [This video](https://youtu.be/Fw0YXqenFoo) looks at choosing the kind of chart most appropriate to the needs of your story
