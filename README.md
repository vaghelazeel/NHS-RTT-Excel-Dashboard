# NHS RTT Waiting Times Dashboard — Excel Project

## What is this?

I built this as a practice project to understand how NHS 
performance data works and to develop Excel skills relevant 
to healthcare data analyst roles.

The dashboard uses real NHS England data published on 
13 August 2026 showing how long patients are waiting 
for treatment across every hospital trust in England.

## Why I built this

I am actively applying for clinical data and healthcare 
analytics roles in the UK. I wanted to build something 
using the same data that NHS analysts actually work with 
rather than generic practice datasets.

## Data

- Source: NHS England — Incomplete Provider Pathways
- Period: June 2026
- Downloaded from: https://www.england.nhs.uk/statistics/statistical-work-areas/rtt-waiting-times/
- File used: Incomplete Provider Jun26 (9M)

## What I did

1. Downloaded the raw NHS Excel file (119 columns, 8000+ rows)
2. Used Power Query to clean the data — removed metadata 
   rows, filtered to 14 key columns, removed summary rows
3. Built a PivotTable showing every NHS trust in England 
   with their total patients waiting and patients seen 
   within 18 weeks
4. Calculated 18-week performance percentage for each trust
5. Applied RAG conditional formatting:
   - Red = below 85% (failing)
   - Amber = 85-92% (at risk)
   - Green = 92%+ (meeting standard)

## What I found

- 6.69 million patients waiting across England
- National performance: 65% within 18 weeks
- NHS constitutional standard: 92%
- Almost every trust is in the Red category
- Only a handful of specialist trusts are meeting the standard

## What I learned

- How Power Query works for real messy data
- What RTT pathways actually mean in NHS context
- How to build benchmarking tables using PivotTables
- Why the 18-week standard matters clinically

## Background

I have an MSc Bioinformatics (Distinction, Teesside University 
2025) and BSc Biotechnology (First Class, Gujarat University 
2023). I am building this portfolio to demonstrate practical 
data skills alongside my academic background as I transition 
into clinical research and healthcare data roles in the UK.

## Next steps for this project

- Add a bar chart of worst performing trusts
- Build a Power BI version of the same dashboard
- Add trend analysis using multiple months of data
