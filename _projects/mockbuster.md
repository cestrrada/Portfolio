---
layout: project
title: Mockbuster
date: May 9, 2019
category: Website

buttons:
  - name: github
    url: https://github.com/cestrrada/MovieRental
    color: btn-light
    icon: fab fa-github
  - name: Website
    url: http://mockbuster.caestrada.com
    color: btn-info
    icon: fas fa-link

featured: mockbuster/featured.png
description: A website for browsing, purchasing and maintaining a movie database.
keywords: website movies database administrator shopping cart api backend frontend development design
---

### Overview
**Mockbuster** is a group project developed for **CST 336: Internet Programming** at CSUMB. The website allows all users to browse movies, add and remove movies from their cart, apply discount codes and check out items. Administrators can additionally add, edit and delete movies from the system as well as view system reports.

#### Project Structure
##### API
The `/api` folder contains all the code necessary to interact with the MySQL database. This includes requesting and editing a movie's information, filtering results the movie database, creating invoices and generating admin reports.

##### Backend
The `/backend` folder consists primarily of database creation files. Here, you can automatically populate your database with a selection of movies found in the provided JSON files. This folder also contains code to log administrators in and out of the system.
