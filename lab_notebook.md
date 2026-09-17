# Lab Notebook — [How to Keep Mycelium Alive]

**Author:** [Mijin Kim] | **Institution ID:** [mvk6435]
**Repository:** [https://github.com/mijin-kim-official/susmat-dossier-mvk6435.git]
**Canonical data store:** (add once established)

> **Standard:** Each entry should contain enough detail for someone
> with similar training to reproduce what you did without asking you.
> — Briney (2023), Research Data Management Workbook


## 2026.09.14. Identifier systems
Observed that training dataset uses three separate identifier systems, they do not currently cross-reference each other. No changes are made to the raw data at this stage. 

## 2026.09.17. Storage and continuity plan
Finished module 2. 

## Characterization — MBC Dormancy–Reactivation Cycle 1 (PLANNED)
**Run ID:** MBC-CYCLE-01-A
**Operator:** Mijin Kim
**Planned date:** [Dec.01.2026]

### Input
- Specimen ID: MBC-24C30-01
- Material type: Mycelium-based composite (MBC)
- Substrate: [Ecovative commercial spawn bag, add 30g of flour as nutrient]
- Specimen geometry: Ø100 mm Petri-dish specimen

### Planned Output
- Regrowth image series: `MBC-24C30-01_C01_regrowth/`
- Mechanical test data: `MBC-24C30-01_C01_mechanical.csv`
- Biomass-density record: `MBC-24C30-01_C01_biomass.csv`

### Method
1. Grow the MBC specimen.
2. Dehydrate by air drying at 24°C until the target moisture level of 30% is reached.
3. Store the dehydrated specimen for 4 days.
4. Crumble the specimen and rehydrate it. 
5. Allow regrowth for 4 days.
6. Measure regrowth performance and material properties.
7. Dehydrate the specimen again before the next cycle.

### Parameters
- Drying temperature: 24°C
- Target moisture level: 30%
- Storage duration: 4 days
- Regrowth duration: 4 days
- Planned cycle limit: 10 cycles

### Measurements
- Viability
- Regrowth speed / rate
- Mechanical properties
- Biomass density / mass

### Instrument / Software
- Drying equipment: [laminar HEPA filtered hood]
- Mechanical testing system: [UTM Instron 5569]
- Image-analysis software: [ImageJ 1.54t (16 May 2026)]
- Image acquisition device: [canon EOS R10]

### Image Analysis Method
Regrowth images will be analyzed using ImageJ 1.54t. Image scale will be calibrated using a dimensional reference included in the image (scale-bar).
The following metrics will be extracted:
- Colony coverage (%)
- Time to 10% coverage (t10)
- Time to 50% coverage (t50)
- Time to 90% coverage (t90)
- Colony radius (mm)
- Colony radial growth rate (mm/day)

### Acquisition Conditions
- Regrowth images will be collected under documented imaging conditions.
- Units for each measurement will be recorded with the raw data.

### Parent / Child Relationship
Parent specimen: `MBC-24C30-01`
Cycle-1 records: `MBC-24C30-01_C01_*`

### Status
PLANNED — actual timestamps, measured values, deviations, and output-file locations will be added after the execution.


---
