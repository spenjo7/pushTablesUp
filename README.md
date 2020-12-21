# pushTablesUp

pushTablesUp contains a simple JavaScript function ( "pushTablesUp()" ), which will convert a nested <table> element into a series of nested <div> elements instead. It also contains a bulk use version ( "pushAllTablesUp()" ) which targets all the tables which are children of a given DOM element. 

WARNING: This function replaces the rendered HTML, rather than providing the modified HTML as an output. ( It's intended for Data Extraction/Homoginization rather than front end production use. )

# Use Case
Primarily, these functions were designed to convert existing HTML Tables into single layer Tables to facilitate any further processing that would iterate through the row and column elements. Significantly, the row/column structure of the parent table should not be impacted.

# Installation
Either include the script as an external .js file or copy/paste it directly into your inline JavaScript. It is very lightweight.

# Use
pushTablesUp( someTableDOMelement ) // Sub-Tables gets converted into nested divs, top level tables are untouched
pushAllTablesUp( someTargetDOMelement ) // pushTablesUp gets called on any table element that is a child of the targetDOMelement

# Author:
Jon Spencer ( 2020 ) 

# License 
Open for anyone to use.