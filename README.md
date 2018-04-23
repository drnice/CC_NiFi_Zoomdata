# CC_NiFi_Zoomdata
DEMO: Showing Credit Card transactions exited from NiFi and posted to Zoomdata API for quick visualizations of data.

# Python Script
The python script picks a random point in the name_cc.csv file in order to generate a random name and fictitious CC number.  The python script also pulls in a random point from CountyStateZip.csv file to place that person in a specific geolocation where the CC tansaction occurred.

One can execute this script from python by executing this command.

python CustomDemo.py 
{"type": "Feature", "properties": {"fraud": true, "date": 1524497642, "fname": "Edward", "lname": "Reed", "cc": "5305 3522 8463 5345", "zip": "54772", "latitude": "45.094148", "longitude": "-91.879257", "city": "Wheeler", "state": "Wisconsin", "county": "Dunn", "cost": 2638}}

The resulting output is a JSON payload.
