Task 1
  1. Variety
The different types of units , some are in AQI and some in celsius 
            The value for some is a string and some are integers 
  2.   Velocity
     If thousands of sensors are sending data every few seconds, then the system must handle    huge amounts of streaming data in real-time.
  3.  Veracity
       One record has { "type": null, "value": 48.0, "unit": "AQI" }
 missing type makes interpretation redundant
4. Volume
         data storage issues 
Data interpretation issues 
 5.  Value
       Traffic analysis - improves emergency response.


Task 2 
 The degree at which data has no errors and is able to fulfill its intended purpose 

Inconsistent timestamp format  - some time stamp value have Post meridiem e.g AM & PM 
 Which clearly distinguishes the time at which the data was collected , This could could to inaccurate data analysis , and the time format is not consistent also 

Empty data - some properties have null attributes eg.    "data": { "type": "traffic_count", "value": null, "unit": "vehicles_per_minute" },

Null data veracity source -  meaning that the data might not accurate e.g  "data_source_veracity": null

Task 3 
1.
{
    "sensor_id": "AQ-01-GER",
    "timestamp": "2025-07-29T08:45:10Z",
    "location": { "latitude": -26.2253, "longitude": 28.1613 },
    "data": { "type": "air_quality", "value": 45.5, "unit": "AQI" },
    "data_source_veracity": 0.95,
    “Aceess_level”: “restricted”
  }

2.  They can use the data to set up traffic so that you don’t make your deliveries in time , eg. organizing fake protests in your scheduled delivery timeframe 
- They can stage robberies against your company so that i am unable to make deadlines and loose the goods at the same time which is bad for business
Data Governance Officer , They ensure compliance with laws (e.g., POPIA) and ethical use of data. 
