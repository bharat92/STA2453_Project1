# STA2453- Course Project 1, Movie Sucess Analysis: An Exploratory Study

This repository has all data and codes used in the exploratory analysis conducted to understand and identify the key drivers of box-office success of a movie. A total of 1403 movies released during the period 2010-2017 was used for this analysis. The final report containing summary of analysis, findings and insights can be found [here](https://bharatlearnstocode.github.io/movie-data-exploration-data-science-exploration/report/STA2453_Project1_Report_BharadwajJanarthanan.html#contents)

## Introduction

The film industry is a key contributor to economy with the global box-office collection totalling to US $ 40.6 billion as of 2017 per the report [9]. Movie production houses need to take decisions on which movie to produce, with the objective to maximise profit and minimise spends. These decisions are usually based upon qualitative measures such as how interesting the plot is, what genre the movie should be under, the movie director, proposed cast, estimated budget and production time for the movie. It therefore becomes critical for production houses to identify key influencers for a movie’s commercial success. In this report, we provide a quantitative approach to identify influential factors for a movie’s commercial success along with their impact.

A candidate set of movie attributes were considered for this study. It includes, genre of the movie, movie review sentiment, cast of the movie, time of release, rating on review portals such as IMDb, Rotten Tomatoes, MetaScore, the MPAA (Motion Pictures Association of America) rating, number of languages the movie has been dubbed in,number of theatres showing the movie and how long the movie has been showing in theatres.

For the purpose of this project, three major data sources were used, OMDB Movies Database, NYTimes Movie Review and Box-Office-Numbers Database. The rest of this report is split into two major sections, the first section describes different data sources used, collection methods, aggregation and merging rules, developed to prepare tidy analytical data.The second section lists out focussed questions and graphs to examine key variable relationships and develop appropriate statistical analyses to quantify the effect of each movie attribute on its box-office success.

## Problem Description

This project is focussed towards addressing the following research questions,

* How well do NYTimes movie critic pick movies that are box office hits?
* Is there a relationship between NYTimes movie review sentinment and critics pick?
* What characteristics of a movie affects it’s revenue?
