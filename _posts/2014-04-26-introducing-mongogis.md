---
layout: page
title: MongoGIS
---

## Background

The GIS, Geographic Information System, industry is booming, especially with the growing reliance on online maps, the rise of location-aware mobile devices, and the wide-spreading geospatial sensors. GIS tech can be one of the key players in the mobile internet, big data, and the internet of things, and shall be an essential infrastructure for the next generation of the global IT industry.


However, the GIS community seems not ready for its destiny. One of the tough challenges is that, in the era of big data, as lots of geo-spatial data keep pouring in, GIS communities have no off-the-shelf solutions to manage all these overwhelming spatial data. Relational spatial databases have played a key role in this field for decades, but now they appears a little tired, and we need a new generation spatial database which could run on large scale clusters and is capable of coping with big spatial data problem. 


MongoDB geospatial part is wonderful and can be deployed to support high performance geo-processing applications. But MongoDB, as a spatial database, is still in its infancy. Both the spatial functionalities within and the GIS tech ecosystem built on are incomplete. you have to write your own ad hoc solutions to glue the existing GIS tools up on it. 

## Mission
Like PostGIS to PostgeSQL, MongoGIS is trying to incorporate several open source gis tools, such as GDAL, Proj4, GEOS, pgRouting, and so on, to empower mongodb to deal with more complex GIS problems.


## Current Work
Currently, we have written an OGR Driver for MongoDB to help GIS tools in the ecosystem work with MongoDB. Source code can be found in our Github repository: [mongodb-gdal-driver] (https://github.com/mongogis/mongodb-gdal-driver).

A talk will be given in the [MongoDB World](http://world.mongodb.com/mongodb-world/session/giving-mongodb-way-play-gis-community), named "Giving MongoDB the Way to Play with the GIS Community" at June 23 - 25, New York City. you may want to attend the meeting so that we can have a thorough discussion about it.
