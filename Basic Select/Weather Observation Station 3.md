Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.
The STATION table is described as follows:

| Field       |   Type     |
|-------------|------------|
| ID          | INTEGER    |
| CITY        | VARCHAR(21)|
| STATE       | VARCHAR(2) |
| LAT_N       | NUMERIC    |
| LONG_W      | NUMERIC    |
---
link:https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true
<h2>Answer:</h2>
<code>select DISTINCT  city from STATION  where mod(id,2)=0;</code>
