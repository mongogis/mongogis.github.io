---
layout: post
title: MongoGIS
---

## Background

The GIS, Geographic Information System, industry is booming, especially with the continued growing reliance on online maps, the rise of location-aware mobile devices, and the wide-spreading spatial sensors. GIS tech can be one of the key players in the mobile internet, big data, and the internet of things, and shall be an essential infrastructure for the next generation of the global IT industry.


Yet, the GIS community seems not prepared for this oppertunity. One of the tough challenges is, that, in the era of big data, as lots of geo-spatial data keep pouring in, GIS communities have no off-the-shelf solutions to manage all these growing volume of spatial data. Relational spatial databases were the leader in this field for decades, whose shortcomings have been well discussed in the context of NoSQL technology. 

In general, GIS communities need a next generation spatial database which could run on large scale clusters and is capable of coping with big spatial data problem. MongoDB geospatial part is wonderful in this context for supporting high performance geo-processing applications. But you have to write your own ad hoc solution to glue the existing GIS tools up on it. in other words the gis tech ecosystem built on mongodb is incomplete. 

## Mission
MongoGIS is set up to bridge the two community, just like PostGIS with PostgeSQL. MongoGIS is trying to incorporate several open source gis tools, such as GDAL, Proj4, GEOS, pgRouting, and so on, to empower mongodb dealing with more complex GIS problems.


## Current Work
Currently, we have written an OGR Driver for MongoDB to help GIS tools in the ecosystem work with MongoDB. Source code can be found in our Github repository: [mongodb-gdal-driver] (https://github.com/mongogis/mongodb-gdal-driver).

More information from [MongoDB World](http://world.mongodb.com/mongodb-world/session/giving-mongodb-way-play-gis-community) at June 23 - 25, New York City.
