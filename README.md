# Pymaceuticals

This homework is about Pymaceuticals and I tried to read two csv file named as data/Mouse_metadata.csv and data/Study_results.csv.

I merged those dataFrame using Pandas. I also printed 249 unique Mice. Get all the data for the duplicate mouse ID and also printed those.

I also cleaned dataFrame and printed 248 unique mice.

I also printed various Bar and Pie Charts. 
I got error when i tried to find out mean as it was giving dataType errors and it was not able to print out.

numbericdataFrame = CapomulindataFrame2.apply(pd.to_numeric, errors='coerce')
