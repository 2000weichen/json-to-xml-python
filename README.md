# json-to-xml-python
A simple python script using the json and lxml libraries for converting JSON structured data to XML

The larger purpose of this script it to migrate content from the Atavist publishing platform to Wordpress. The problem is that Atavist only exports to JSON, which has an array of html content split into 'chapters' as well as an object containing metadata about the publication (i.e. post date, author, revisions.)

This script uses python (specifically the lxml and json libraries) to restructure the JSON data as an XML feed that Wordpress can interpret and map fields to its own data structure. 
