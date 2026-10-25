# Texas Land & Energy Atlas

An interactive map of Texas and Louisiana for land, oil and gas, power, carbon capture and storage, lithium and geothermal work. Everything on it comes from public sources.

**Open the map:** https://thegreenmachines.github.io/texas-land-energy-atlas/

## What's on it

- **Petroleum land system:** Texas original land surveys and abstracts, Louisiana section-township-range grid
- **Surface parcels and tax appraisal:** Montgomery, Angelina, Sabine and Newton counties, TX, and DeSoto Parish, LA; statewide Texas parcels and roads (live)
- **Ranches and large landholdings:** ranch, cattle and farm entities (100+ ac) and private owners of 1,000+ ac in the 71 Texas counties east of Dallas plus DeSoto and Calcasieu parishes, from 2026 appraisal and assessor rolls
- **Oil and gas:** Texas GLO units, Louisiana units and state leases, RRC wells and pipelines (live), drilling permits approved since Oct 2025 (RRC W-1 and SONRIS), USGS assessment units for the Austin Chalk, Smackover, Haynesville and Frio
- **LNG and gas transport:** Texas and Louisiana LNG export terminals with owned tracts and export volumes, EIA transmission pipelines, market hubs, ship channels, state-to-state gas flows, and a 10 MMcf/d well-to-LNG path simulation
- **Pipeline systems:** Energy Transfer (Houston Pipeline, Trunkline, Florida Gas, Bayou Bridge, crude and NGL lines, terminals, plants), Williams (Transco and Central gathering), Enbridge (Texas Eastern, Bakken Pipeline System, DCP Midstream NGL), Boardwalk / Gulf South with the proposed Texas Gateway, Targa coastal gathering, Sempra Infrastructure, Golden Pass Pipeline, CP Express, DeLa Express (proposed) and the Enerfin Neale system
- **Geology and seismic:** Gulf Coast salt domes, mapped faults, USGS assessment units, the Burr Ferry 3D permit outline
- **Electricity:** transmission lines, operating and planned power plants, ERCOT's planned 765-kV lines (STEP)
- **Federal and state minerals:** federal lands, Texas state mineral and submerged lands, active state leases, Louisiana water bottoms and reserved minerals
- **CCS:** Class VI applications, CO2 emitters, saline, coal-seam and depleted-field storage capacity
- **Lithium, solar, wind and geothermal:** USGS lithium data, Smackover trend, Arkansas brine units, solar resource, wind turbines, geothermal favorability
- **Surface and environment:** FEMA flood zones, wetlands, bare-earth elevation (live), forests, rainfall, detailed coastal bays and ship channels

Quick-layer buttons at the top of the sidebar switch between oil and gas, power, critical minerals and CCS views. Click anywhere on the map for details about what's there.

## How it works

The site is static: `index.html` plus data files in `sv/`, `surveys/` and `svb/`. Live layers are fetched from public government services (Texas RRC, SONRIS, FEMA, USFWS, USGS, TxDOT, TxGIO) in your browser.

## Sources and accuracy

Each layer's popup or sidebar note names its source and date. Some layers are traced from published maps and are approximate; their notes give the expected accuracy. This map is for reference and screening only. It is not a survey, a title opinion, or a substitute for checking the source records.
