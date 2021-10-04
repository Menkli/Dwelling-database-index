# Dwelling-database-index  

## Background  
During the course of the cooperation with MSF, the humanitarian working group has generated thousands of dwelling polygons. The polygons were generated based on satellite images. Every polygon that represents a dwelling has certain characteristics, such as its location and the date the respective satellite image was taken. Other characteristics include its size, ...[add more]. The polygons are currently stored in a database. Recent activities include that the dwelling polygons shall function as samples for convolutional neural networks (CNN), which aim at automatized dewlling extraction from satellite imagery.

## Objective
All the dwelling data in the database is supposed to receive an identifier which is not only unique but also descriptive. It should contain:
- a consecutive number  
- a timestamp
- its location, based on a DGGS  

Question: Why can we not have the timestamp and the location stored as an attribute of the dwelling?
