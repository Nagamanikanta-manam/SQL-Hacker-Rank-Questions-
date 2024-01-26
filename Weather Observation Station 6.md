Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from STATION. Your result cannot contain duplicates.

Input Format

The STATION table is described as follows:

| Field       |   Type     |
|-------------|------------|
| ID          | INTEGER    |
| CITY        | VARCHAR(21)|
| STATE       | VARCHAR(2) |
| LAT_N       | NUMERIC    |
| LONG_W      | NUMERIC    |

where LAT_N is the northern latitude and LONG_W is the western longitude.

--
link:https://www.hackerrank.com/challenges/weather-observation-station-6/problem?isFullScreen=true

<h2>Answer:</h2>
<code>select distinct city from STATION  where substr(city,1,1) in ('a','e','i','o','u');</code>
