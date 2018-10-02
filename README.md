00:00 - begyndte at installere Linqpad

00:30 - kigger på hvordan man connecter til en MYSQL database fra linqpad

01:00 - læser og prøver hvordan joins fungere i linq



Linqpad down

https://www.linqpad.net/Download.aspx

connect to mysql database with linq

https://www.cdata.com/kb/tech/mysql-ado-linqpad.rst
https://forum.linqpad.net/discussion/965/liinqpad-5-database-connections

How to use linqpad

linqpad connections string

http://www.linqpad.net/entityframework.aspx
https://www.connectionstrings.com/sqlite/

how to connect linqpad to sql server

https://forum.linqpad.net/discussion/1473/connecting-to-server-on-network
https://itknowledgeexchange.techtarget.com/itanswers/connect-linqpad-sql-server/
https://stackoverflow.com/questions/7010735/connect-linqpad-to-remote-sql-server?rq=1
https://stackoverflow.com/questions/6629786/how-can-i-connect-to-mysql-via-linqpad

mysql vs linq

https://www.lingq.com/en/

linq language

http://www.tutorialsteacher.com/linq/sample-linq-queries
https://code.msdn.microsoft.com/101-LINQ-Samples-3fb9811b
https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/basic-linq-query-operations

linq client side joins

https://stackoverflow.com/questions/16531527/which-is-better-in-performance-client-side-joins-or-server-side-joins

client side joins

linq client side joins

https://social.msdn.microsoft.com/Forums/en-US/3dc6b6c0-416c-4453-a9b3-0232256d765a/linq-statements-server-side-or-client-side?forum=adodotnetentityframework
https://stackoverflow.com/questions/9115708/how-to-write-linq-query-to-prevent-duplicates-joins
http://weblogs.thinktecture.com/pawel/2016/04/entity-framework-prevent-redundant-joins.html
https://docs.telerik.com/data-access/developers-guide/profiling-and-tuning/profiler-and-tuning-advisor/data-access-profiler-client-side-linq-queries

1. Det første problem vi stødte ind i var at connect til databasen fra linqpad til den mysql database som var givet i opgaven.
vi søgte på forskellige måder men kunne stadig ikke få en connection. Til sidst fandt vi et svar som forklarede at vi
skulle hente en anden driver og connecte med den. Da vi gjorde det gik det igennem med det samme.
2. næste ting som vi brugte noget tid på var at finde ud af hvad linq egentlig var. Vi fandt mange ting som sage det var OR
og man kunne bruge det sammen med mange forskellige SQL database typer. Vi fandt også ud af man kunne bruge forskellige sprog sammen
med linqpad som gjorde os mere forvirret
3. Sidste del vi fandt svært var hvad client side join var. Vi havde en idé om at det var client som lavede joins i stedet for 
databasen/serveren. Vi søgte både om hvordan det virkede igennem alle databaser og tilsidst fokuserede på hvordan linq håndterede problemet
