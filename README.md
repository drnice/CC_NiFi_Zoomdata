# Introduction
Visualizing Realtime data can be a challenge.  However the combination of NiFi to route data and publish data to Zoomdata's Upload API make it extremely easy to interact with real time data and get a sense of what is being generated immediately.  Click here to see what can be done - https://customerdemo.zoomdata.com/zoomdata/visualization/58065a83e4b013a41a10f762+5abb0636e4b07b5eab254299?__target=embedded&key=ayYB6FPrna This demonstration repo will provide users the ability to recreate this demo using NiFi and Zoomdata.'

# The Python Script
The python script picks a random point in the name_cc.csv file in order to generate a random name and fictitious CC number.  The python script also pulls in a random point from CountyStateZip.csv file to place that person in a specific geolocation where the CC tansaction occurred.

One can execute this script from python by executing this command.

python CustomDemo.py 
{"type": "Feature", "properties": {"fraud": true, "date": 1524497642, "fname": "Edward", "lname": "Reed", "cc": "5305 3522 8463 5345", "zip": "54772", "latitude": "45.094148", "longitude": "-91.879257", "city": "Wheeler", "state": "Wisconsin", "county": "Dunn", "cost": 2638}}

The resulting output is a JSON payload.
