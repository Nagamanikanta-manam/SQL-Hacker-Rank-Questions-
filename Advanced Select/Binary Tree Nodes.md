<h2>Solve it on <a href="https://www.hackerrank.com/challenges/binary-search-tree-1/problem?isFullScreen=true">hacker rank</a></h2>
<code>
select a.n,
case
when a.p is null 
then "Root"
when a.n not in (select b.p from bst b where  not(b.p is null))
then "Leaf"
else "Inner"
end
from bst a order by a.n;
</code>
