GScholar-2-Excel
================

A piece of JS that exports Google Scholar results to Excel friendly format. 

Google Scholar has been used widely used search tool among researchers. While other tools, such as IEEEeXplore, Scopus, EngineeringVillage etc. provide an option to export search results, Google Scholar lack this functionality. This plugin
adds the functionality to Google Scholar to export search results.

Google Scholar is a recommended tool to perform snowball sampling  - an emerging method to perform systematic literature reviews and maps [1]. Performing forward snowball (discovering papers that cite a particular paper) implies significant effort to move discovered papers from Google Scholar to a spreadsheet for further screening. The plugin is aimed to automate this step. 


[1] C. Wohlin, “Guidelines for Snowballing in Systematic Literature Studies and a Replication in Software Engineering,” in Evaluation and Assessment in Software Engineering, 2014.



# Installation

For Chrome users:
-----------------
1. Install TamperMonkey https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
2. Goto Dasboard -> Utilities tab
3. Import tmScripts.txt provided


For FireFox users:
------------------
1. Install GreaseMonkey
2. Click Add New Script
3. Paste the code from given JS file to the code editor
4. Save


How to use:
-----------
At the top menu of any Google Scholar search page is a link Export
Whenever you click it, a overlay will show up offering to copy tab separated list of 
displayed results. Copy-paste the contents to Excel.


Troubleshoot:
-------------
If you do not see Export link on the top, make sure the script is configured to run on google scholar pages. 
