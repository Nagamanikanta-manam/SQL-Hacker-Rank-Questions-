Query a list of CITY and STATE from the STATION table.
The STATION table is described as follows: 
---
+-------------+------------+
| Field       |   Type     |
+-------------+------------+
| ID          | INTEGER    |
| CITY        | VARCHAR(21)|
| STATE       | VARCHAR(2) |
| LAT_N       | NUMERIC    |
| LONG_W      | NUMERIC    |
+-------------+------------+
---
link:https://www.hackerrank.com/challenges/weather-observation-station-1/problem?isFullScreen=true
<h2>Answer:</h2>
<code>select city,state from STATION ;</code>
