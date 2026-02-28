# About

I have many years of experience working with data and was working with ‘Big Data’ before the term came into popular use. I also have extensive experience with high volume/low latency OLTP systems. I have repeatedly demonstrated the ability to create productized data processing applications that customers are happy to buy. I am currently in charge of promoting new aspects of Volt’s technology, in a role which spans Sales, Marketing and Engineering. I have four patents in the areas of distributed databases and database backups.

# Areas of Expertise

* Transaction processing: The design and deployment of sub-second OLTP systems that handle thousands of updates per second while providing low latencies and high availability.
* Big Data: Extensive experience designing and working with systems that handle billions of records and Terabytes of data each and every day. 
* Distributed databases, specifically error correcting conflict resolution algorithms and bandwidth efficient Active-Active systems. 
* World class high performance database design and performance tuning knowledge.
* Commercial application development in Java.

# Personal Attributes

* Pragmatic and creative problem solver with a proven track record of resolving situations involving multiple technologies and groups of people with differing objectives.
* Can understand every aspect of a complicated problem space simultaneously.
* Expertise in leading blue sky projects that involve leading edge technology while maintaining a business perspective.
* Experience leading global specialist teams effectively and efficiently.

# Links

* [LinkedIn](https://www.linkedin.com/in/srmadscience)
* [PersonalWebSite](https://www.rolfe.ie/)
* [Substack](https://srmadscience.substack.com/)

# Interesting repositories

Over time I've accumulated around 100 repos. The more interesting public ones are below.

## Volt Active Data

At Volt Active Data I am the authority on how to use the product in the real world. This 
involves writing large quantities of Volt centric code.

### Sandboxes and benchmark code

This is publicly available code that's used for demos and frequently benchmarks.

* [voltdb-charglt](https://github.com/srmadscience/voltdb-charglt) Charging Demo: A non-trivial telco focused Volt Active Data example
* [voltdb-xdcrchargingdemo](https://github.com/srmadscience/voltdb-xdcrchargingdemo) Version of charging demo that has changes needed to work in an XDCR universe.
* [voltdb-tatpbenchmark](https://github.com/srmadscience/voltdb-tatpbenchmark) An VoltDB implementation of "Telecom Application Transaction Processing" benchmark
* [volt-tpcc-sandbox](https://github.com/srmadscience/volt-tpcc-sandbox) TPCC implementation.
* [voltdb-subway](https://github.com/srmadscience/voltdb-subway) Sandbox based on real Transport For London data set
* [voltdb-javacache-sandbox](https://github.com/srmadscience/voltdb-javacache-sandbox) A sandbox application for a VoltDB JSR107 implemtation.
* [voltdb-simbox-with-rules](https://github.com/srmadscience/voltdb-simbox-with-rules) Simbox demo with DML driven rule engine
* [voltdb-simbox](https://github.com/srmadscience/voltdb-simbox) Simbox detection sandbox
* [voltdb-policysandbox](https://github.com/srmadscience/voltdb-policysandbox) A Sandbox Policy Implementation for VoltDB
* [voltdb-cvmsandbox](https://github.com/srmadscience/voltdb-cvmsandbox) Customer Value Management Sandbox
* [voltdb-aggdemo](https://github.com/srmadscience/voltdb-aggdemo) A demonstration of how VoltDB can be used for the kind of streaming aggregation tasks common in Telco
* [volt-aggdemo-voltsp](https://github.com/srmadscience/volt-aggdemo-voltsp) Demo of Volt's new stateless processing functionality
* [voltdb-iotcars](https://github.com/srmadscience/voltdb-iotcars) A voltDB IOT sandbox for matching electric cars with chargers and using a prepaid phone to pay


### XDCR Examples 

"XDCR" stands for "Cross Data Center Replication", also known as "Active-Active"
* [voltdb-xdcr-aware-client](https://github.com/srmadscience/voltdb-xdcr-aware-client)  Client that can switch XDCR clusters if needed.
* [voltdb-xdcrchargingdemo](https://github.com/srmadscience/voltdb-xdcrchargingdemo) Version of charging demo that has changes needed to work in an XDCR universe.

### General Examples 

* [voltdb-h2o-mojo-demo](https://github.com/srmadscience/voltdb-h2o-mojo-demo) A demonstration of how to use H2O's MOJOs in VoltDB
* [voltdb-task-and-migrate-demo](https://github.com/srmadscience/voltdb-task-and-migrate-demo) A demo of Volt's scheduled tasks and MIGRATE functionality.
* [voltdb-rules](https://github.com/srmadscience/voltdb-rules) A prototype rules engine.
* [voltdb-nwaysettlement](https://github.com/srmadscience/voltdb-nwaysettlement) N Way Settlement with compound procs example
* [volt-flightcache](https://github.com/srmadscience/volt-flightcache) A example of how to use Volt compound procedures for rapid lookup of flight data
* [volt-timeseries](https://github.com/srmadscience/volt-timeseries) Prototype time series data handling
* [volt-simple-kafka](https://github.com/srmadscience/volt-simple-kafka) A simple Kafka demo for Volt Active Data
* [volt-vlmc2](https://github.com/srmadscience/volt-vlmc2) Example code for tracking interbank exposure. 
* [volt-vlmc](https://github.com/srmadscience/volt-vlmc) Example code for tracking interbank exposure.
* [voltdb-deleteallrows](https://github.com/srmadscience/voltdb-deleteallrows)Example of how to delete all rows
* [volt-secure-tokens](https://github.com/srmadscience/volt-secure-tokens) Simple demo to show how volt can be used to provide secure tokens
* [voltdb-clite](https://github.com/srmadscience/voltdb-clite) A simplistic sandbox charging demo.
* [binarydiff](https://github.com/srmadscience/binarydiff) This repository contains FastAndRuthlessDiffImpl, which is used to reduce network bandwidth when working with byte[] objects that are being changed slightly by a client before being sent back to a server.
* [smartdenserank](https://github.com/srmadscience/smartdenserank) A Dense Rank leaderboard example.
* [volt-activeSD101](https://github.com/srmadscience/volt-activeSD101) Tutorials for moving Kafka workloads to Volt Active Data

### Volt Utilities

* [voltseconvert](https://github.com/srmadscience/voltseconvert) VoltSeConvert is used to do a crude, once-off conversion from Oracle or TimesTen to VoltDB
* [voltseconvertoracleexample](https://github.com/srmadscience/voltseconvertoracleexample) An example of VoltSeConvert in use
* [voltdb-autojar](https://github.com/srmadscience/voltdb-autojar) Builds and loads a JAR file for procedure classes with the "@IsAVoltDBProcedure" annotation. 
* [voltdb-schemabuilder](https://github.com/srmadscience/voltdb-schemabuilder) Utility to create and load procedure JAR files
* [VoltSeUtils](https://github.com/srmadscience/VoltSeUtils) Core utility classes for VoltDB SE

### Examples of LRU Cache Code

Volt is an in memory DB. Usually not a problem, but if it is I implemented a prototype LRU cache framework.

* [lrucache_client](https://github.com/srmadscience/lrucache_client)
* [lrucache_client_cassandra](https://github.com/srmadscience/lrucache_client_cassandra)
* [lrucache_client_oracle](https://github.com/srmadscience/lrucache_client_oracle)
* [lrucache_client_postgres](https://github.com/srmadscience/lrucache_client_postgres)
* [lrucache_sdk](https://github.com/srmadscience/lrucache_sdk)
* [lrucache_server](https://github.com/srmadscience/lrucache_server)

### Examples of generated code to call TMForum APIs

[TMForum](https://www.tmforum.org/oda/open-apis/) is a telco industry body that defines standard APIs 
for the many different API calls used in the mobile phone network. I have written code that takes the 
public API definitions and generates stub Volt code to support them. This code is in a private repo, but 
examples of generated code for [TMF654 - Prepay Balance Management](https://www.tmforum.org/resources/standard/tmf654-prepay-balance-management-api-user-guide-v4-0-0/)
are in the public repos below.

* [TMF654-PrepayBalance-v4.0.0-client](https://github.com/srmadscience/TMF654-PrepayBalance-v4.0.0-client)
* [TMF654-PrepayBalance-v4.0.0-server](https://github.com/srmadscience/TMF654-PrepayBalance-v4.0.0-server)
* [TMF654-PrepayBalance-v4.0.0-volt](https://github.com/srmadscience/TMF654-PrepayBalance-v4.0.0-volt)


### YCSB

* [volt-run-ycsb](https://github.com/srmadscience/volt-run-ycsb) Runs a YCSB benchmark on Volt, assuming AWS

### Other Code

* [addToDeploymentDotXml](https://github.com/srmadscience/addToDeploymentDotXml)
* [binarydiff](https://github.com/srmadscience/binarydiff)

## Telco Charging Demo and Benchmark

As a side project I have implemented the charging benchmark for REDIS, SingleStore and MongoDB. Note that none of 
these have been tested at scale, as each one would run up an AWS bill to properly test.

* [voltdb-charglt](https://github.com/srmadscience/voltdb-charglt) Charging Demo: A non-trivial telco focused Volt Active Data example
* [s2-charglt](https://github.com/srmadscience/s2-charglt) SingleStore implemention of charglt
* [redis-charglt](https://github.com/srmadscience/redis-charglt) REDIS implementation of ChargLT
* [mongodb-charglt](https://github.com/srmadscience/mongodb-charglt) Mongo implementation of Charglt

## JDBCWizard

When I moved back to Ireland from America I wrote and sold a product called "OrindaBuild", subsequently renamed "JDBCWizard".
It looks at stored procedure definitions in an Oracle database, and writes all the Java code needed to run them. This 
isn't benign or simple, as Oracle's JDBC implementation allows you to pass multiple different kinds of complex objects
back and forth, but the resulting API is a nightmare. Which is why I automated it. While I sold the product to some well 
known businesses, I eventually moved on to other things.

Below are some JDBCWizard related examples. The real code is (obviously) in a private repo.

* [jdbcwizard-pub](https://github.com/srmadscience/jdbcwizard-pub) Public utility library for JDBCWizard. This code contains useful functionality for working with Oracle, JDBC and PL/SQL
* [jdbcwizard-dbhell](https://github.com/srmadscience/jdbcwizard-dbhell) This is a set of Oracle schemas designed to fully exercise what is syntacticly possible JDBCWizard can generate Java code to run all the examples here.
* [jdbcwizard-test-code](https://github.com/srmadscience/jdbcwizard-test-code) Examples of code generated to test JDBCWizard.
* [jdbcwizard-demo-code](https://github.com/srmadscience/jdbcwizard-demo-code) Examples of code generated for the built in demo.

## Home IOT

I got fed up with the lack of a countdown timer on my Bosch dishwasher, so I [implemented one](https://www.linkedin.com/posts/srmadscience_mqtt-at-home-for-fun-and-profit-i-have-activity-7425472798124523521-Yu3g?utm_source=share&utm_medium=member_desktop&rcm=ACoAAABZpVsBZ3JZV_O5Q_nBmZtQXy3bpIGlQK8) using a Raspberry Pi and an ePaper display

* [bosch-dishwasher-control](https://github.com/srmadscience/bosch-dishwasher-control) An example of reading MQTT data from a bosch dishwasher and updating an ePaper sign.
* [hcpy-hacked](https://github.com/srmadscience/hcpy-hacked)

## Other

* [filewrangling-utils](https://github.com/srmadscience/filewrangling-utils) Utility classes for fixing flat files
* [gdocs2md](https://github.com/srmadscience/gdocs2md) Convert a Google Drive Document to the Markdown format, suitable for publishing

