Query the list of CITY names ending with vowels (a, e, i, o, u) from STATION. Your result cannot contain duplicates.

Input Format

The STATION table is described as follows:
|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |
where LAT_N is the northern latitude and LONG_W is the western longitude.
link:select distinct city from station where  city like '%[a,e,i,o,u]';
<h2>Answer:</h2>
<code>select distinct city from station where  city like '%[a,e,i,o,u]';</code>


