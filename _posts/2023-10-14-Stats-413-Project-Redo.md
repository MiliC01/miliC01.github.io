---
layout: post
title: "Estimating the Area of Nations Project Revision"
author: "Milagros N. Cortez"
categories: statistics
tags: [R, Monte Carlo Sampling, Beta Distribution, Volume Integraton, R Markdown]
image: "Screenshot 814.png"
listed:
- R
- Monte Carlo Sampling
- Beta Distribution
- Volume Integration
- R Markdown
link: "Area of Nations Revision.pdf"
type: "PDF"
updated: "14/07/2023"
---

## About

This project is a revision of a previous project for Stat 413 at the University of Alberta. The project consists on designing an algorithm to estimate the area of any country on Earth using Monte-Carlo simulation. The algorithm simulates the latitude and longitude points from the surface of the Earth, and uses a lookup table to match the simulated coordinates to the country of interest. Given a country’s name as input, the algorithm will report the estimated area of that country, along with a 90% confidence bound around that estimate.
As part of this revision we will use volume integration to find the area of a spherical rectangle bound by latitude and longitude coordinates instead of using a sinusoidal projection that converts the coordintes into distances, which are used to find the area of land that captures the country of interest which is later used to apply Monte-Carlo sampling. 
