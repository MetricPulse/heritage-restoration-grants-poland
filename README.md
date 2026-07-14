# Heritage Restoration Grants in Poland
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0066CC?style=for-the-badge)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

Interactive Power BI dashboard and GIS analysis of projects funded under the first edition of the Polish Government Heritage Restoration Programme.

<img width="4150" height="2400" alt="image" src="https://github.com/user-attachments/assets/2dd81563-4189-414e-aa7e-4e162643dfbc" />
>


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

<img width="2075" height="1200" alt="z_woj__page-0001" src="https://github.com/user-attachments/assets/b5d61569-1c49-46fe-89c6-d3434fc8a081" />


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

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/91c71340-e48c-4d9f-8bc2-646bb8c43077" />
>


The GIS component presents a county-level choropleth map showing funding per resident (PLN), calculated using county population statistics published by Statistics Poland (2023).

---

| Tool | Purpose |
|------|---------|
| Power BI | Interactive dashboard development |
| DAX | Measures and KPIs |
| Power Query | Data cleaning and transformation |
| Excel | Data preparation |
| QGIS | Spatial analysis and cartography |

---

## Data Sources

- Polish Government Heritage Restoration Programme – First Edition Results 
- Statistics Poland (GUS) – Population (2023) 
- GADM 4.1 Administrative Boundaries 

---
### References

- https://www.gov.pl/web/finanse/wyniki-naboru
- https://bdl.stat.gov.pl/bdl/dane/podgrup/temat
- https://gadm.org/

---
## Repository Structure

```
data/
gis/
images/
powerbi/
README.md
```
