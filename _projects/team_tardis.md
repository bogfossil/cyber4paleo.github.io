---
title: Team TARDIS
layout: page
concept: Time Adorned Resource Descriptions in Science (TARDIS)
---

*Working to bring the CSIRO geologic time RDF resources into several data holdings


# Team Members

  * Douglas Fils  -- Consortium for Ocean Leadership / Open Core Data
  * Bob Arko -- IEDA / SESAR
  * Alexandra Noronha -- University of Texas  
  * Anders Noren -- CSDCO 
  * Shannon Peters -- Macrostract


# Project Goal

To take the resources from https://www.seegrid.csiro.au/wiki/CGIModel/GeologicTime
and use them to add properties to geologic time resources, like data files across
several group.   Simon Cox has noted that if we can get interest in these he
would spend some time to update the latest ICS timescales and also 
OWL time http://def.seegrid.csiro.au/isotc211/iso19108/2002/temporal

# Questions

  * How to "age" the CSDCO data:  Neotoma age models, Geo Deep Dive possible
  * Connect CSIRO/ICS and Macrostrat concepts ID's via GeoLink Graph


# Links

  * SESAR GeoLink RDF for time
  * Macrotrat;  API : https://macrostrat.org/api 
  * CSIRO   https://www.seegrid.csiro.au/wiki/CGIModel/GeologicTime

# Steps  
  * SESAR
    * 30K samples with ages..  mix of assignment and analytic  (don't know when one or other)
    * put in prov even if it is "unknown"
    * put in URI's from SESAR graph (sample URI is associated with age URI)  (using GeoLink hasGeologicAge)
    * above is available at http://data.geolink.org/sparql in SESAR graph
  * Open Core
    * use age models to find age range of core and assign with CSIRO ICS 2014  (using GeoLink hasGeologicAge)
    * publish to GeoLink graph class dataset / digitalobject
  * General
    * create cross link to Macrostrat resources and place in GeoLink
    * Demo the utility how?
