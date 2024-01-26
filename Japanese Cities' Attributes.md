Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.

The CITY table is described as follows: 
----
|  Field | Type |
|---|---|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRY CODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |
---
link:https://www.hackerrank.com/challenges/japanese-cities-attributes/problem?isFullScreen=true
<h1>answer:</h1>
<code>select * from city where countrycode='JPN';</code>
