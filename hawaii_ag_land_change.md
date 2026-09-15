---

editor_options: 
  markdown: 
    wrap: 72
---

# Exploring Agricultural Land Use Change in Hawaiʻi (2015 → 2020)

**DS422 — Geocomputation in R**

In this mini-project, you will explore how agricultural land use has changed across Hawaiʻi between 2015 and 2020, using openly available geospatial datasets from the Hawaiʻi Statewide GIS Program. You will create maps, conduct spatial comparisons, and communicate changes in land use through engaging and informative visual storytelling.

------------------------------------------------------------------------

## ✅ Data

Download the GeoJSON files and place both in your `data/` folder in your **DS422-Geocomputation** project:

| Year | Dataset | Link |
|---------------------|-------------------------------|---------------------|
| 2015 | Agricultural Land Use Baseline | <https://geoportal.hawaii.gov/datasets/HiStateGIS>::agricultural-land-use-2015-baseline/about |
| 2020 | Hawaiʻi Agricultural Lands | [https://geoportal.hawaii.gov/items/342ee6c7547f45ddbfc07caf4ca2887d](https://geoportal.hawaii.gov/datasets/342ee6c7547f45ddbfc07caf4ca2887d_19/explore?location=20.566850%2C-157.274800%2C7) |

------------------------------------------------------------------------

## ✅ Software Tools You May Want to Use

Mapping & Visualization: - [`mapview`](https://r-spatial.github.io/mapview/) — fast interactive mapping - [`mapgl`](https://r-spatial.github.io/mapgl/) — advanced vector tile maps - [`tmap`](https://cran.r-project.org/package=tmap) — powerful thematic mapping - [`leaflet`](https://rstudio.github.io/leaflet/) — interactive web mapping - [`ggplot2`](https://ggplot2.tidyverse.org/) — publication-quality mapping with `geom_sf()`

Data Wrangling & Tables: - [`dplyr`](https://dplyr.tidyverse.org/) - [`tidyr`](https://tidyr.tidyverse.org/) - [`readr`](https://readr.tidyverse.org/) - [`sf`](https://r-spatial.github.io/sf/) — essential for spatial data handling

Color & Classification: - [`RColorBrewer`](https://cran.r-project.org/package=RColorBrewer) - [`viridis`](https://cran.r-project.org/package=viridis) - [`classInt`](https://cran.r-project.org/package=classInt)

Flow Visualization: - [`ggalluvial`](https://corybrunson.github.io/ggalluvial/) — Sankey-style flows - [`networkD3`](https://christophergandrud.github.io/networkD3/) — interactive flow diagrams

Popups & Interactivity: - [`leafpop`](https://r-spatial.github.io/leafpop/)

You do *not* need to use all of these — just explore what supports your creative ideas.

------------------------------------------------------------------------

## ✅ Questions to Inspire You

Pick a few that interest you — or create your own!

### 🗺️ Cartographic Design

- What is the **highest-quality map** you can create with this data?
- How can you improve user experience with:
  - styling, legends, labeling, basemaps, accessibility?

### 🌱 Change in Agricultural Land

- Is there **more or less** agricultural land in 2020 compared to 2015?
- How much did agricultural acreage change **overall**?
- Which islands gained or lost the most?
- What is the **percent change** in total agricultural land?

### 🌺 Crop Type Changes

- Which specific crop categories **increased or decreased** the most?
- Can you align crop names between 2015 and 2020 to make valid comparisons?
- Can you represent crop transitions with a **Sankey diagram**?

### 🗺️ Spatial Change Detection

- Where did land shift **into** agriculture?
- Where did agriculture convert to **other uses**?
- Can you produce a **gain/loss** map of agricultural land?
- Can you map specific crop conversions (e.g., Coffee → Pasture)?

------------------------------------------------------------------------

## ⭐ Creative Expansion Ideas

These are optional, but may spark ideas: - Compare **island-level** land use change - Create a **story map** or interactive dashboard - Add **contextual layers** such as roads or county boundaries - Focus on one island to provide a **deep spatial narrative** - Provide **policy or environmental implications** of these changes

------------------------------------------------------------------------

## 🎯 Deliverable

Your mini-presentation should: ✅ Ask an interesting question\
✅ Analyze change over time and space\
✅ Include at least one map and one additional visual\
✅ Clearly explain why your findings matter

📌 During the **last 20 minutes of class**, each student will: - Share their screen - Present **for 2 minutes** - Show the **map(s)** and **insights** they are most proud of

------------------------------------------------------------------------

## 🧠 Your Turn

You are encouraged to: - Explore - Experiment - Tell a spatial story

Agricultural land in Hawaiʻi is changing — what can you reveal about *how* and *why*?
