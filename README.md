# dynamo-revit-tools
a collection of practical tools for revit  

 dynamo packages required to install: 
(Python3, Iron python2.7, archi-lab, datashapes, crumple, clockwork)

These scripts were designed to work with out the box Revit title blocks &
 work with the users existing project scopeboxes,levels & view template data. 

View & sheet scripts

Batch create views & sheets from the named scope boxes and levels for a common 
set of service plans ie fire alarm

there are 2 scripts, 1 for regular views & 1 for dependent views:  
1- Single zone Floorplan Views & Sheets 
Creates views and/or sheets & places views on sheets if both are selected and run.  

2- Multi zone Dependent Floorplan Views & Sheets
Creates a parent view with dependent views and/or sheets& places views on sheets 
if both are selected and run.

scripts can be customised to use shared parameters to extend automation of the title block  
but work out the box to suit revit default title block parameter settings  

Purge scripts

1-Purge project-cleans selected reference planes, levels, scope boxes & view templates
2-Purge unused views & sections-lists unused elements for quick deletion from project 

Rename scripts

1-renames either levels, or scope boxes in a central user interface 
2-replaces any words in view and sheets to bulk rename

Replicate legend

This script takes a legend that has been placed on an existing sheet and 
replicates it in the same location on other sheets.

To run the script you will need to open the sheet with an existing legend placed
in the position you want to replicate. when the script is opened click on the legend
and run the script, it will then replicate across all user selected sheets.     
