# logeater
Log-Aggregation Tools for BIND 9 logs


Example use of ```logeater-queries```:

```
cat query.n | ./logeater-queries -s | column -t -s ":"
Query-Statistics
21385              total queries ( 100 % )
20471              iterative queries ( 95 % )
914                recursive queries ( 4  % )
863                queries over TCP ( 4  % )
16987              queries with EDNS support ( 79  % )
15197              queries indicate DNSSEC support ( 71  % )
8804               queries with DNSSEC validation disabled (CD-flag) ( 41  % )
1571               queries TSIG signed ( 7  % )
```

Tested with BIND 9.10 and BIND 9.11.

Binary versions of the ```logeater``` tool can be found at http://packages.menandmice.com/logeater/
