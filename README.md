# Weekly AQI Change Prediction
Goal: Given air quality and weather data from adjacent cities in the US over a period of time, predict whether the air quality index (AQI) will increase or decrease in the following week.

### Dataset
The data for this project was obtained from the U.S. Environmental Protection Agency (EPA) via the Air Data on AWS (EDAP) public portal. ([Direct Access Portal](https://awsedap.epa.gov/public/single/?appid=efa6d1bf-4cab-4e17-9e14-8046adfe9249&sheet=3495c3da-aca4-494b-a1d8-d6d6a0571cbc&opt=currsel%2ctxmenu&bookmark=6ebdada3-18f6-4831-a4b6-9d6e1a14a446))

**Time Period:** 01/01/2025 till 31/12/2025 

**Data Types:**
- Meteorological - Hourly
- PM2.5 - Hourly 
- Ozone - Hourly

**Station Selection:**
| State | Selected Monitoring Stations
|-------|--------|
| California | LPO010 |
| Texas | ACL188, PAL190 |
| New York | NIC001, WFM105 |
| Illinois | BVL130, STK130 |
| Florida | IRL141, CNS011 |
| Colorado | GTH161, ROM206 |

Note on California: Station LPO010 was the only one in the selected region that provided a complete and consistent hourly record for all three required data types (particularly PM2.5) within the chosen timeframe. Therefore, it was selected as the sole representative for this state.
