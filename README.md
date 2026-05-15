# Dragon# Dragon Kingdom Overview Dashboard – README

## Project Overview

The **Dragon Kingdom Overview Dashboard** is an interactive Power BI dashboard designed to analyze and visualize dragon-related statistics such as fire power, speed, treasure hoards, rider bond, dragon types, and elemental distribution. The dashboard provides a fantasy-themed analytical experience with dynamic visuals and KPI tracking. 

---

# Dashboard Features

## Key Performance Indicators (KPIs)

The dashboard highlights major performance metrics:

* **Total Dragons:** 210
* **Average Fire Power:** 77.45
* **Average Speed:** 72.70
* **Total Hoards:** 299
* **Average Rider Bond:** 59.90

These KPIs provide a quick overview of the dragon kingdom’s overall status. 

---

# Visualizations Included

## 1. Top Dragon by Fire

Horizontal bar chart displaying dragons with the highest fire power.

Top dragons include:

* Embermaw
* Cinderstorm
* Starflame
* Smolderfang
* Nightroar

Purpose:

* Compare dragon fire capabilities
* Identify strongest dragons

---

## 2. Dragons by Element

Donut/Pie chart showing dragon distribution based on elemental powers.

Elements include:

* Fire
* Water
* Ice
* Darkness
* Light
* Poison
* Air
* Metal

Purpose:

* Understand elemental diversity
* Analyze dominant dragon elements

---

## 3. Dragons by Type

Bar chart representing the count of dragon species.

Types include:

* Western Dragon
* Drake
* Wyvern
* Faerie Dragon
* Lung Dragon
* Celestial Dragon
* Sea Dragon
* Serpent
* Shadow Dragon

Purpose:

* Compare dragon population by species

---

## 4. Wingspan VS Flight Speed

Scatter/Bubble chart analyzing the relationship between:

* Wingspan (ft)
* Flight Speed (mph)

Purpose:

* Identify aerodynamic efficiency
* Compare size vs speed trends

---

## 5. Dragon Details Table

Detailed table containing:

* Dragon Name
* Type
* Element
* Origin Region
* Fire Power
* Flight Speed
* Treasure Hoards

Example dragons:

* Ashenveil
* Blazehorn
* Cinderstorm
* Embermaw
* Frostclaw

Purpose:

* Drill-down analysis
* Detailed dragon insights

---

# Filters & Slicers

The dashboard includes interactive filters for:

* Type
* Element
* Origin Region
* Population Status

Population statuses:

* Common
* Endangered
* Mythic
* Rare
* Stable
* Vulnerable

These slicers help users perform focused analysis dynamically.

---

# Dashboard Design

## Theme

* Fantasy/Dragon Kingdom inspired UI
* Dark red background with golden highlights
* Medieval-style typography and visuals

## Design Elements

* Dragon illustrations
* Fantasy color palette
* Responsive chart layout
* Interactive filtering system

---

# Tools Used

* **Power BI Desktop**
* DAX Measures
* Interactive Visualizations
* Data Modeling
* Slicers & Filters

---

# Suggested DAX Measures

## Total Dragons

```DAX
Total Dragons = COUNT(Dragon[DragonID])
```

## Average Fire Power

```DAX
Avg Fire Power = AVERAGE(Dragon[FirePower])
```

## Average Speed

```DAX
Avg Speed = AVERAGE(Dragon[FlightSpeed_mph])
```

## Total Hoards

```DAX
Total Hoards = SUM(Dragon[TreasureHoards])
```

## Average Rider Bond

```DAX
Avg Rider Bond = AVERAGE(Dragon[RiderBond])
```

---

# Insights Generated

* Fire dragons dominate the kingdom.
* Western Dragons are the most common species.
* Some dragons combine high wingspan with exceptional flight speed.
* Treasure hoards vary significantly among dragon types.
* Mythic and endangered dragons can be isolated using slicers.

---

# Future Improvements

Possible enhancements:

* Add map visualization for origin regions
* Include dragon age analysis
* Add battle performance metrics
* Implement tooltip pages
* Add animated navigation buttons
* Create mobile responsive layout

---

# Conclusion

The **Dragon Kingdom Overview Dashboard** demonstrates advanced Power BI dashboarding concepts using fantasy-themed data visualization. It combines storytelling, KPI monitoring, filtering, and interactive analytics into a visually engaging business intelligence solution. 
