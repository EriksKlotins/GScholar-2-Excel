GScholar-2-Excel
================

A piece of JS that exports Google Scholar results to Excel friendly format. 

Google Scholar has been used widely used search tool among researchers. While other tools, such as IEEEeXplore, Scopus, EngineeringVillage etc. provide an option to export search results, Google Scholar lack this functionality. This plugin
adds the functionality to Google Scholar to export search results.

Google Scholar is a recommended tool to perform snowball sampling  - an emerging method to perform systematic literature reviews and maps [1]. Performing forward snowball (discovering papers that cite a particular paper) implies significant effort to move discovered papers from Google Scholar to a spreadsheet for further screening. The plugin is aimed to automate this step. 


[1] C. Wohlin, “Guidelines for Snowballing in Systematic Literature Studies and a Replication in Software Engineering,” in Evaluation and Assessment in Software Engineering, 2014.




# Installation

For now, the plugin is a simple JavaScript file and requires another plugin to run. In Chrome TamperMonkey works well, for FireFox I recommend GreaseMonkey. 

## For Chrome users:
-----------------
1. Install TamperMonkey https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
2. Download the export plugin (https://github.com/EriksKlotins/GScholar-2-Excel/archive/master.zip)
3. Goto TamperMonkey -> Dasboard -> Utilities tab
4. Import excel-export.js file 


## For FireFox users:
------------------
1. Install GreaseMonkey (How to install FF extensions: https://support.mozilla.org/en-US/kb/find-and-install-add-ons-add-features-to-firefox)
2. Download the export plugin (https://github.com/EriksKlotins/GScholar-2-Excel/archive/master.zip)
3. Click Tools -> GreaseMonkey -> New user script
4. Fill in "GScholar2Excel" (remove quotes) in both name and namespace fields, click Ok
4. Paste the contents of excel-export.js file to the code editor
5. Save

## Troubleshoot:
-------------
If you do not see Export link on the top, make sure the script is configured to run on google scholar pages. Click on TamperMonkey icon to see what scripts are actually running.


# How to use:
-----------
At the top menu of any Google Scholar search page is a link Export.
Whenever you click it, a overlay will show up offering to copy tab separated list of 
displayed results. Copy-paste the contents to Excel.


# Support and suggestions

If you are using this plugin and find it useful or have any suggestions, please drop me an email at eriks.klotins@gmail.com 

Hearing from people who find this plugin useful motivates further development and support of this plugin.


## Acknowledgments

This script is developed in close collaboration with: Ricardo B., Magnus W., Ramtin J., Usman M. and others from Blekinge Institue of Technology, Dept. of Software Engineering. 


