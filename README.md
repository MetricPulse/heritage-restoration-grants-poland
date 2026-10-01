# Heritage Restoration Grants in Poland

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0066CC?style=for-the-badge)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

Interactive Power BI dashboard and GIS analysis of projects funded under the first edition of the Polish Government Heritage Restoration Programme.

<img width="2075" height="1200" alt="Heritage Restoration Grants dashboard" src="https://github.com/user-attachments/assets/1075842d-86ac-4dd5-8530-557a736eba9c" />

---

## About the Project

The Polish Government Heritage Restoration Programme supports the conservation and restoration of historical monuments through grants awarded to local governments.

This project analyzes the results of the programme's **first edition**, announced in **July 2023**, covering **4,807 funded projects** with a total value of approximately **PLN 2.51 billion**.

The analysis combines business intelligence techniques in Power BI with spatial analysis in QGIS to explore how heritage funding is distributed across Poland.

The project focuses on both the **scale of funding** and its **regional intensity**, using funding per resident as an additional spatial indicator.

---

## Analytical Questions

The analysis focuses on several questions:

- How is heritage restoration funding distributed across Polish voivodeships?
- Which counties received the highest total funding?
- Which types of heritage sites receive the largest share of funding?
- How does funding intensity differ between counties?
- How does the picture change when funding is considered relative to population?
- Are regional patterns visible that are not apparent from total funding alone?

---

## Data & Methodology

The project combines programme-level funding data with population and administrative boundary data.

### Main Indicators

The Power BI analysis includes:

- Total funding
- Number of funded projects
- Average grant value
- Funding by voivodeship
- Funding by county
- Funding by heritage site type
- Funding per resident

### Funding per Resident

A county-level **funding per resident** indicator was calculated by dividing total heritage funding by the county population.

This measure is used as a descriptive indicator of funding intensity and helps account for differences in population size between counties.

> **Methodological note:** Funding per resident should be interpreted as a measure of funding intensity rather than a measure of funding need, programme effectiveness or fairness of allocation.

---

## Dashboard

<img width="2075" height="1200" alt="Power BI dashboard" src="https://github.com/user-attachments/assets/b5d61569-1c49-46fe-89c6-d3434fc8a081" />

The Power BI dashboard provides an interactive overview of the programme's funding distribution.

### Main Components

**Funding by Voivodeship**  
Compares the total value of grants across Polish voivodeships.

**Project Share by Heritage Site Type**  
Shows the distribution of funded projects across different types of heritage sites.

**Top 10 Counties by Funding**  
Ranks counties according to the total value of received funding and provides additional information on project count and average grant value.

**Funding by Heritage Site Type**  
Compares the total funding allocated to different heritage categories.

**Regional Filters**  
Allow the analysis to be narrowed down to selected voivodeships and heritage site types.

---

## Key Metrics

| Metric | Description |
|---|---|
| Total Funding | Total value of grants included in the analysis |
| Projects | Number of funded projects |
| Average Grant | Average value of a funded project |
| Funding by Voivodeship | Total funding allocated across voivodeships |
| Funding by County | Total funding allocated across counties |
| Funding per Resident | Funding relative to county population |
| Heritage Site Type | Classification of the funded heritage project |

---

## Key Findings

The analysis highlights several regional and structural patterns in the programme's first edition.

- The programme covered **4,807 projects** with total funding of approximately **2.51 billion PLN**.
- **Mazowieckie** received the highest total funding among voivodeships, with approximately **265.6 million PLN**.
- Other highly funded voivodeships included **Wielkopolskie (218.6 million PLN)**, **Lubelskie (206.0 million PLN)** and **Małopolskie (201.9 million PLN)**.
- **Religious heritage** represents the largest heritage site category in the analysed programme, accounting for the largest share of both projects and funding.
- At county level, **Kielecki County** recorded the highest total funding in the displayed ranking, at approximately **22.4 million PLN**.
- Looking at funding per resident provides a different perspective from total funding and reveals substantial variation in funding intensity across Polish counties.

---

## GIS Analysis

<img width="3507" height="2480" alt="County-level funding per resident map" src="https://github.com/user-attachments/assets/91c71340-e48c-4d9f-8bc2-646bb8c43077" />

The GIS component presents a **county-level choropleth map** showing heritage restoration funding per resident across Poland.

Funding values were combined with county population statistics published by **Statistics Poland (GUS)** to calculate the indicator.

The map was created in **QGIS** using administrative boundaries from **GADM 4.1**.

The spatial analysis provides an additional perspective that cannot be obtained from absolute funding totals alone.

---

## Tools

| Tool | Purpose |
|---|---|
| Power BI | Interactive dashboard development |
| DAX | Measures and analytical calculations |
| Power Query | Data cleaning and transformation |
| Excel | Data preparation |
| QGIS | Spatial analysis and cartography |

---

## Data Sources

- Polish Government Heritage Restoration Programme – First Edition Results
- Statistics Poland (GUS) – Population data for 2023
- GADM 4.1 – Administrative boundaries

---

## References

- https://www.gov.pl/web/finanse/wyniki-naboru
- https://bdl.stat.gov.pl/bdl/dane/podgrup/temat
- https://gadm.org/

---

## Repository Structure

```text
heritage-restoration-grants-poland/
│
├── data/
├── gis/
├── images/
├── powerbi/
└── README.md
