# National Grid ESO

National Energy System Operator (NESO) — formerly National Grid ESO — is the UK electricity
system operator responsible for balancing electricity supply and demand across Great Britain.
NESO publishes open data APIs covering carbon intensity forecasts, electricity demand, generation
mix, ancillary services, balancing costs, and system operational data.

## APIs

### Carbon Intensity API

Real-time and forecast carbon intensity data for Great Britain.

- **Base URL:** `https://api.carbonintensity.org.uk`
- **Docs:** https://carbon-intensity.github.io/api-definitions/
- **Auth:** None required
- **License:** CC BY 4.0

Key capabilities:
- National and regional carbon intensity (14 GB regions + postcode lookup)
- 96+ hour ahead forecasts
- Generation mix by fuel type (gas, coal, nuclear, biomass, hydro, imports, solar, wind)
- Historical data with date-range queries (up to 14 days per request)
- Statistics with block averaging (up to 30 days)

### NESO Data Portal API (CKAN)

Programmatic access to hundreds of electricity system datasets via the CKAN API.

- **Base URL:** `https://api.neso.energy/api/3/action/`
- **Docs:** https://www.neso.energy/data-portal/api-guidance
- **Auth:** None required
- **Rate Limits:** 1 req/sec (catalog), 2 req/min (datastore)

Key dataset categories:
- Ancillary Services (Fast Reserve, Firm Frequency Response, STOR)
- Demand forecasts (day-ahead, historic)
- Generation data (wind, solar, embedded)
- Balancing costs
- Constraint management
- Network charges (TNUoS)
- Trading data
- Future Energy Scenarios
- Connection registers

## Links

- Portal: https://www.neso.energy/data-portal
- GitHub: https://github.com/carbon-intensity
- News: https://www.neso.energy/news-and-events
- Support: box.OpenData.ESO@nationalgrideso.com

## License

Data is provided under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
licence and the NESO Open Licence. Commercial use is permitted with attribution.
