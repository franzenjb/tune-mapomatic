# Tune-Mapomatic

**Drop the needle on any Red Cross map resource.**

A fast, searchable interface for 1,000+ American Red Cross map resources, forecasts, hazard maps, and GIS services. Replaces scrolling through the 500+ link [ARC Map Catalog](https://maps.redcross.org/website/maps/ARC_Map_Links.html).

## Features

- **Instant Search** - Fuzzy search across all resources: "SC chapter", "earthquake risk", "FEMA REST", "hurricane"
- **Clickable US Map** - Tile grid map, click any state to see its resources
- **Region Highlighting** - Selecting a state highlights its ARC region partners
- **Filter Chips** - Filter by level (Chapter/Region/Division), type, source, format
- **1,000+ Resources** - All 50 states, DC, 5 territories, national atlas, hazard maps, forecasts, tropical, monitoring, partner services
- **Code Lookup** - Search 3,240 counties by name, FIPS, chapter, ECODE, RCODE, or DCODE (ARC FY2026 geography)
- **Copy URL** - One-click URL copy for any resource
- **Zero Dependencies** - Single HTML file + one data file, no build step, no external libraries

## Resources Included

| Category | Count | Examples |
|----------|-------|---------|
| Chapter Maps | 101 | State chapter boundary maps (PDF) |
| Region Maps | 106 | Multi-state region maps (PDF) |
| State Maps | 300+ | FIPS codes, hydrology, demographics, federal lands |
| Boundary Data | 8 | 2026 geodatabases (GDB) and alignment spreadsheets |
| National Atlas | 34 | Division/region/chapter wall maps |
| Hazard Maps | 22 | Earthquake, flood, hurricane, tornado, wildfire, tsunami, volcano |
| Forecasts | 32 | SPC outlooks, WPC rainfall/heat/winter, fire weather, graphical forecasts |
| Tropical | 32 | NHC outlooks, JTWC, storm surge, tracking charts, SST, hurricane history |
| Monitoring | 52 | GOES satellite, RADAR, USGS earthquakes, drought, fire, air quality, HazMat |
| International | 12 | Canada, Mexico, Caribbean, Oceania, world maps |
| Partner Services | 25 | FEMA, NWS, USGS, Census REST endpoints |
| Evacuation Maps | 12 | Coastal state storm surge/evacuation |
| Declarations | 12 | FEMA Presidential Disaster Declarations by region |

## Data Source

All resources sourced from [maps.redcross.org](https://maps.redcross.org/website/maps/ARC_Map_Links.html), current as of FY'26 (January 2026).

## Boundary Data Downloads (2026)

Direct links to the most important downloads:

- [Master (ALL Boundaries)](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_2026.gdb.zip)
- [Chapters Only](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_Chapter_2026.gdb.zip)
- [Regions Only](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_Region_2026.gdb.zip)
- [Divisions Only](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_Division_2026.gdb.zip)
- [States Only](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_States_2026.gdb.zip)
- [DRA/Territories](https://maps.redcross.org/website/Services/Data/Master_RC_Geo_DRA_Territories_2026.gdb.zip)
- [Chapter Alignment w/ Demographics (XLSX)](https://maps.redcross.org/website/Services/Data/Chapter_Alignment_Public_with_Demogs.xlsx)

## Keyboard Shortcuts

- `/` - Focus search bar
- `Escape` - Clear all filters and search

## Part of Red Cross GIS Tools

[Red Cross GIS Tools](https://franzenjb.github.io/GeoJSON-Creation-Tool/) | [Map Catalog Source](https://maps.redcross.org/website/maps/ARC_Map_Links.html)
