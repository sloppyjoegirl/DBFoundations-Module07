# DBFoundations-Module07
**User-Defined Functions**

**Introduction**

In this assignment I will outline the following topics: 

-	When to use a user-defined function
-	The differences between scalar, inline, and multi-statement functions

**When should you use a User-Defined Function?**

User-defined functions allow you to build complex sets of routines (that recall data) that you can call on later without having to write all the code out again. You should therefore use them when you will be required to use the same or similar statements in SQL when performing repetitive tasks. While modular programming is the primary benefit of UDF’s, there are additional benefits that encourage you to use UDFs whenever possible, including allowing faster execution of code and reducing network traffic [(source: User-Defined Functions - SQL Server | Microsoft Docs).](https://docs.microsoft.com/en-us/sql/relational-databases/user-defined-functions/user-defined-functions?view=sql-server-ver16) 

**What are the differences between scalar, inline, and multi-statement functions?**

-Scalar: scalar functions return a single value as defined by the return clause of the UDF
-Inline: inline functions, also called inline table valued functions, return a table of values (vs the single value returned by a scalar function). The return clause defines that the data should be returned as a table by saying “RETURN TABLE”. 
-Multi-statement: multi-statement functions are similar to inline functions in that they return a table of values. However, multi-statement functions allow for much more flexibility in how data is returned in the table. With a multi-statement function, you can define in the return clause how data is organized and displayed in the table. 

**Summary**

User-Defined Functions allow for you to write more complex programs in SQL without having to spend hours writing and re-writing code. Additionally, it also allows for modular programming that is easier to keep organized and read. 
