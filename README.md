# A-Semi-automatic-Data-Integration-process

This repository collects all the results obtained during the process described in the paper: "A Semi-automatic Data Integration Process of heterogeneous databases".

In particular:

**CarShopping System.pdf**

This file shows the results obtained for the *CarShopping system*. This system relates to an international company, *"Car Shopping"*, which buys collectible model cars, trains, trucks, buses and ships directly from manufacturers and sells them to distributors around the world. Car Shopping uses two relational databases to support its business, one for human resource management (e.g. offices, employers) and one for marketing and sales (e.g. customers, orders or products).

**Cooking System.pdf**

This file shows the results obtained for the *Cooking system*. This system relates to the world of Trentino Alto Adige cuisine. *"Cooking"* uses three data sources relational databases (made available by the Ministry of Public Administration) . *"Prodotti Tradizionali"* (a list of traditional Trentino products by name, category, curiosity, description, conservation/processing methods and production area), *"Ricette"* (a collection of typical Trentino recipes with traditional products such as appetizers, first courses, desserts), *"Ospitalità"* (containing the essential data relating to catering).

**Panda System.pdf**

This file shows the results obtained for the *Panda system*. This system aims to carry out analyses on typical university activities, focusing attention on student productivity. It consists of two data sources. The first "*SDI"* relating to an attendance recording system, in the university context, used in the period between 2008 and 2010 by the University of Molise. Currently, the system database maintains approximately 18,000 attendance tuples and over 54,000 user tuples. The second *"UnderDesk"* however, is a web application that allows users to be able to share their notes. The system maintains more than 54,000 users and 3,000 notes.

**Plants System.pdf**

This file shows the results obtained for the *Plants system*. This system has the objective of building a Data Warehouse for the management of nursery plants services, integrating tw*sources from two different companies (but which nonetheless work in the nursery plants sector). In particular, these are two relational database. *"DB Vivaio E-commerce"*, a database of a nursery plants company that sells plants and provides related services; *"DB Vivaio Interventi"*, a database of a company that deals exclusively with the supply of nursery services, consisting of activities similar to those carried out by the first company.


In each file there are:
* Input
  * the relational databases of input

* Syntactic Analysis
  * the dendrogram produced by the syntactic analysis
  * the result obtained from the clustering of the syntactic analysis

* Semantic Analysis
  * the dendrogram produced by the semantic analysis
  * the SOM grid obtained during the semantic analysis
  * the result obtained from the semantic analysis clustering

* Output
  * the reconciled source schema
