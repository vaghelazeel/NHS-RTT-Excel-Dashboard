# NHS RTT Waiting Times Dashboard

## Overview

This project analyses NHS Referral to Treatment waiting times 
across all hospital trusts in England using official NHS England 
data from June 2026. The goal was to build a performance 
benchmarking dashboard that mirrors the kind of work done by 
NHS intelligence and data analysts.

[Dashboard Top](dashboard_top.png.png)

[Dashboard Bottom](dashboard_bottom.png.png)

## Data

Source: NHS England, Incomplete Provider Pathways

Period: June 2026, published 13 August 2026

Downloaded from the NHS England statistics portal:
https://www.england.nhs.uk/statistics/statistical-work-areas/rtt-waiting-times/

## Tools Used

Microsoft Excel, Power Query, PivotTables, Conditional Formatting

## What I Built

I started with the raw NHS file which had 119 columns and over 
8,000 rows including metadata, weekly breakdown columns and 
summary rows. I used Power Query to clean it down to 14 relevant 
columns and filtered out the noise.

From there I built a PivotTable summarising every NHS trust in 
England showing total patients waiting and total patients seen 
within 18 weeks. I then calculated the 18-week performance 
percentage for each trust and applied RAG conditional formatting 
to show performance against the NHS constitutional standard.

Red means below 85%, which is failing the standard.
Amber means between 85% and 92%, which is at risk.
Green means 92% or above, which is meeting the standard.

## Key Findings

6.69 million patients are currently on incomplete pathways 
across England.

The national 18-week performance stands at 65%, against an 
NHS constitutional target of 92%.

The majority of trusts are in the Red category, reflecting 
the scale of the NHS waiting list backlog following the 
pandemic.

A small number of specialist and community trusts are meeting 
or exceeding the 92% standard.

## My Background

I have an MSc Bioinformatics with Distinction from Teesside 
University (2025) and a BSc Biotechnology First Class from 
Gujarat University (2023). I am building this portfolio to 
demonstrate practical data and analytics skills as I apply 
for clinical research and healthcare data roles in the UK.
