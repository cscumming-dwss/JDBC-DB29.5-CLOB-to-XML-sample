# JDBC-DB29.5-CLOB-to-XML-sample
This simple JDBC example demonstrates connecting to DB2 and parsing CLOBs with XML

This program reads from two repositories on two different db2 systems. 
It read in a CLOB that contains XML into a string (db29.5 driver does not properly process CLOBs) and parses it looking for a particular attribute, changes that attribute and updates it in the database

