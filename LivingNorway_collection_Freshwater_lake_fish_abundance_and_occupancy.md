---
title: "LivingNorway collection: Freshwater lake fish abundance and occupancy"
author: "Anders G. Finstad"
date: "5/1/2021"
output: html_document
---

![Foto: Anders G. Finstad (cc-by-4.0)](https://live.staticflickr.com/7571/27368187191_706d6e3a80_c_d.jpg)

## About
This collection contains datasets with information on lake fish abundance or occupancy. This means either quantitative sampling like gill-nets or electrofishing, or information on presence/absence. Typically there are two main sources of information. 

* Environmental surveys with gillnets or similar sampling-protocol enabling inference of relative abundance
* Questionnaires or interviews with local stockholders

The geographic scope is Fennoscandian with main focus on Norway. The Fennoscandian perspective is included since biogeograpical patterns and environmental gradients does not make sense in a Norwegian perspective without including transnational data (ecology don't stop at the border principle ..). 

## Technical comments 

### Geogrefferencing
Most of the data are georefferenced with coordinate given as centeroid of lake polygon. There are exeptions, for exampel, some Swedish datasets give lake coordinates for outlet and some locations are given with litterate coordinates. Lakes are additionally in some instances identified with national LakeID, and in some instances not. Datsets containing Fennoscandian scale lake polygons GIS data and lists of lake identifiers (IDs) are listed under additional resources below.  

## Additional resources 

The following additional resources are useful for interpreting data and putting data in context. 

### Environmental datasets and other contextualizing resources

* The [Fennoscandian lake register](https://bird.unit.no/resources/9b27e8f0-55dd-442c-be73-26781dad94c8/content) https://doi.org/10.21400/ghj5z8i1 is a transnational dataset of lake poloygons and lakeIDs covering Fennoscandia. 

### R code and procedures 

* The GitHub repro [lakefish](https://github.com/emmaSkarstein/lakefish) gives usefull snippets of code for e.g. spatially matching lake fish observation coordinates with lake polygons and lakeIDs. 


