<h2>Solve on<a href="https://www.hackerrank.com/challenges/the-pads/problem?isFullScreen=true"> Hacker Rank</a></h2>

<h2>Solution</h2>
<code>
select 
case 
 when occupation='Doctor' 
  then concat(name,'(D)')
 when occupation='Actor' 
  then concat(name,'(A)')
 when occupation='Singer' 
  then concat(name,'(S)')
 when occupation='Professor' 
  then concat(name,'(P)')
 END 
from OCCUPATIONS  order by name;
</code>
<code>
select concat('There are a total of ',count(occupation),' ',lower(occupation),'s.') from OCCUPATIONS  group by occupation order by count(occupation),occupation ;
</code>
