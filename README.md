# North Carolina Crime Map (Interactive Visualization)

This project is an interactive crime map visualizing county-level crime data across North Carolina for the years 2018–2023. Built using [Leaflet.js](https://leafletjs.com/) and additional open-source libraries, it allows users to explore how crime totals vary by year and location.

## 🌍 Features

- **Interactive Map** centered on North Carolina
- **Year Toggle Buttons**: Easily view crime data from 2018 to 2023
- **Color-Coded Counties**: Gradient color scale based on total reported crimes
- **Tooltips** with county names and popups showing total crime count
- **Zoom-to-County** on click
- **Legend and Article Link** included on the map

## 🛠️ Technologies Used

- [Leaflet.js](https://leafletjs.com/) - Interactive maps
- [leaflet-ajax](https://github.com/calvinmetcalf/leaflet-ajax) - Load GeoJSON asynchronously
- [chroma.js](https://gka.github.io/chroma.js/) - Color scale
- [jQuery](https://jquery.com/) - DOM manipulation and utility functions
- [CARTO](https://carto.com/) - Dark base map tiles

## 📊 Data Sources

- Crime statistics: [NC SBI Crime Statistics Reports](https://www.ncsbi.gov/SSRV?report=/UCR/IndexOffensesByAgencyInCounty)
- Geographic boundaries: [NC OneMap](https://www.nconemap.gov/)

## 🔗 Related Article

> Main article: [Violent Crime Up in NC, Down Nationwide](https://www.carolinajournal.com/violent-crime-up-in-nc-down-nationwide/)