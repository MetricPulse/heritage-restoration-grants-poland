# Heritage Restoration Grants in Poland

Interactive Power BI dashboard and GIS analysis of projects funded under the first edition of the Polish Government Heritage Restoration Programme.

![Dashboard](<<img width="4150" height="2400" alt="z_woj_ (1)" src="https://github.com/user-attachments/assets/645aebbc-0110-4075-a0dc-df98100547e6" />


---

## About

The Polish Government Heritage Restoration Programme supports the conservation and restoration of historical monuments through grants awarded to local governments.

This project analyzes the results of the programme's **first edition**, announced in **July 2023**, covering more than **4,800 funded projects** with a total value exceeding **PLN 2.5 billion**.

The analysis combines business intelligence techniques in Power BI with spatial analysis in QGIS to explore regional differences in heritage funding across Poland.

---

## Project Objectives

- analyse funding distribution across voivodeships and counties
- compare funding by heritage site type
- identify counties receiving the highest grants
- calculate funding per resident
- visualize regional disparities using GIS

---

## Dashboard

![Dashboard](<img width="566" height="325" alt="image" src="https://github.com/user-attachments/assets/d2be435d-7ace-4116-9e5b-0975f7973568" />
)

Key indicators include:

- Total funding
- Number of funded projects
- Average grant value
- Main heritage category
- Funding by voivodeship
- Funding by heritage site type
- Top funded counties

---

## GIS Analysis

![Funding per resident](<img width="3507" height="2480" alt="zabytki" src="https://github.com/user-attachments/assets/32f24af5-8c78-406b-95be-2c2d2d6160ce" />


The GIS component presents a county-level choropleth map showing funding per resident (PLN), calculated using county population statistics published by Statistics Poland (2023).

---

## Tools

- Power BI
- DAX
- Power Query
- Excel
- QGIS

---

## Data Sources

- Polish Government Heritage Restoration Programme – First Edition Results
- Statistics Poland (GUS) – Population (2023)
- GADM 4.1 Administrative Boundaries

---

## Repository Structure

```
data/
gis/
images/
powerbi/
README.md
```
