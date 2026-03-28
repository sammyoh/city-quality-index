# Baltimore Source Catalog

This project is centered on building a Baltimore quality-of-life index from a mix of civic, demographic, and amenity data.

## Priority domains

- affordability and housing
- safety
- food access
- parks and green space
- restaurants and nightlife
- things to do
- education

## Recommended sources

| Domain | Source | Why it matters | Notes |
| --- | --- | --- | --- |
| Neighborhood indicators | BNIA Vital Signs / Community Statistical Areas | Strong Baltimore-specific geography and neighborhood indicators | Best long-term neighborhood analysis anchor |
| Housing and affordability | Census ACS API | Income, rent, home value, renter/owner mix, population | Good baseline source without paid market data |
| Rent benchmark | HUD Fair Market Rents / SAFMR | Useful affordability benchmark | Better as a benchmark than a true neighborhood rent feed |
| Commerce and amenities | Open Baltimore Licenses | Helpful for identifying establishment types such as groceries, taverns, and other businesses | Strong enrichment layer for neighborhood activity |
| Safety | Baltimore Police open data | Crime and service-call context | High-value source for safety analysis |
| Amenities and points of interest | OpenStreetMap Overpass | Flexible for groceries, museums, bars, theaters, parks, and other place-based signals | Practical open source for livability data |
| Education | Maryland Report Card | School performance and accountability data | Good later addition for family-oriented scoring |

## Useful framing for the final product

This source mix supports a product that can compare neighborhoods or geographies across:
- affordability
- green space access
- food access
- amenity density
- safety trends
- family-friendliness

## Source links

- Open Baltimore portal: [https://data.baltimorecity.gov/](https://data.baltimorecity.gov/)
- Baltimore Police open data: [https://www.baltimorepolice.org/crime-stats/open-data](https://www.baltimorepolice.org/crime-stats/open-data)
- Open Baltimore licenses service: [https://opendata.baltimorecity.gov/egis/rest/services/NonSpatialTables/Licenses/FeatureServer](https://opendata.baltimorecity.gov/egis/rest/services/NonSpatialTables/Licenses/FeatureServer)
- Census ACS API: [https://www.census.gov/programs-surveys/acs/data/data-via-api.html](https://www.census.gov/programs-surveys/acs/data/data-via-api.html)
- BNIA: [https://bniajfi.org/](https://bniajfi.org/)
- BNIA data downloads: [https://bniajfi.org/vital_signs/data_downloads/](https://bniajfi.org/vital_signs/data_downloads/)
- Maryland Report Card: [https://reportcard.msde.maryland.gov/](https://reportcard.msde.maryland.gov/)
- HUD Fair Market Rents: [https://www.huduser.gov/portal/datasets/fmr.html](https://www.huduser.gov/portal/datasets/fmr.html)
- Overpass API guide: [https://wiki.openstreetmap.org/wiki/Overpass_API/Language_Guide](https://wiki.openstreetmap.org/wiki/Overpass_API/Language_Guide)
