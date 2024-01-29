<a href="https://www.hackerrank.com/challenges/what-type-of-triangle/problem?isFullScreen=true">Hacker Rank Link</a>
<h2>Answer:</h2>
<code>
  SELECT CASE 
    WHEN A + B <= C OR A + C <= B OR B + C <= A THEN 'Not A Triangle'
    WHEN A = B AND B = C THEN 'Equilateral'
    WHEN A = B OR A = C OR B = C THEN 'Isosceles'
    ELSE 'Scalene'
END
FROM TRIANGLES;
</code>
