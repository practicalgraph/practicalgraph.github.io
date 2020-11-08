---
title: "An Introduction to the Graph Ecosystem"
permalink: /databases
author_profile: false
sidebar:
  nav: "databases"
---

The graph ecosystem is one of, if not the fastest growing sector of the database market, according to <a href="https://db-engines.com/en/ranking_categories" target="_blank">DB-Engines.com</a>. In the past few years, the number of new offerings in the graph database space is mind boggling and difficult to track. For people new to the graph database space, trying to understand what each one does and where it fits, is a daunting task. Our hope here to provide a high-level overview of the graph ecosystem to offer some context around what every kind of databases does well and how it fits in the overall landscape. We will examine each of the options in enough detail so that you understand how they work, what they do, and why you might or might not chose them for your project. 

## Database versus Frameworks 
At the highest level, the graph  ecosystem is divided into graph frameworks and graph databases. While there is no universally accepted definition of what constitutes a framework versus a database, we are going to use the following meanings: 

[Graph Frameworks](frameworks.md) - Systems and tools where data is loaded from an independent data source such as an RDBMS, HDFS, or text file by the application or user. Data is then loaded and processed using graph structures and constructs frequently on a distributed analytics platform such as Hadoop or Spark. 

[Graph Databases](db.md) - Systems or tools that handle the storage, loading, and processing of data using graph constructs. This construct is analogous to how a relational database is responsible for not only the processing of the data but also the storage of it as well. 
To compare and contrast the different options available we are going to be using a hypothetical scenario of analyzing Twitter data for everyone in New York City. We will use this scenario to explain what sort of questions each database type is optimized to answer and why it works best on those problems. 


