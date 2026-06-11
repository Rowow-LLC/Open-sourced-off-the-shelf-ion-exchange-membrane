# Membrane Characterization Data

`membrane_characterization.csv` is the community dataset for the open-source ion exchange membrane. Anyone who builds the membrane and measures it can add a row by pull request, or attach numbers to a Build Report issue.

The file currently contains a placeholder example row. It will be replaced as measured datasets come in, starting with Rowow's baseline membrane.

## Column Definitions and Units

| Column | Definition | Units |
|---|---|---|
| sample_id | Unique ID, your choice (e.g. USERNAME-001) | text |
| date | Date membrane was cast | YYYY-MM-DD |
| builder | GitHub username or name | text |
| membrane_type | cation, anion, or mixed | text |
| resin_product | Resin brand/product used | text |
| resin_fraction_vol_pct | Resin loading by volume | % |
| binder | PVC or CPVC | text |
| solvent | THF, MEK, cyclohexanone, etc. | text |
| additives | Fiberglass, fumed silica, mesh reinforcement, or none | text |
| thickness_mm | Average film thickness | mm |
| wet_or_dry_measured | Whether thickness was measured wet or dry | text |
| area_resistance_ohm_cm2 | Areal resistance in test solution | ohm cm2 |
| ionic_conductivity_mS_cm | Through-plane conductivity | mS/cm |
| iec_meq_g | Ion exchange capacity, dry basis | meq/g |
| permselectivity_pct | Apparent permselectivity from membrane potential | % |
| water_uptake_pct | Mass gain after soaking, dry basis | % |
| linear_swelling_pct | Length change wet vs dry | % |
| test_solution | Electrolyte used for electrochemical measurements | text |
| test_temp_C | Test temperature | C |
| exposure_duration_h | Longest continuous exposure/operation observed | hours |
| mechanical_notes | Cracking, flexibility, burst behavior | text |
| visual_notes | Uniformity, bubbles, color | text |
| data_source | Issue/PR link, video link, or "direct" | text |

## Low-Cost Measurement Protocol

These methods are chosen so a small lab or home builder can produce comparable numbers.

### Thickness
Measure with a micrometer or calipers at 5+ points, report the average. State wet or dry.

### Water Uptake and Swelling
Dry the sample, weigh and measure length. Soak in deionized water 24 h, blot, weigh and measure again.
Water uptake % = (wet mass - dry mass) / dry mass x 100. Swelling % = (wet length - dry length) / dry length x 100.

### Ion Exchange Capacity (cation membranes)
Soak sample in 1 M HCl 24 h to convert to H+ form, rinse until rinse water is neutral. Soak in 1 M NaCl 24 h to displace H+ into solution. Titrate that solution with standardized NaOH using phenolphthalein. IEC = mmol NaOH / dry mass in g.

### Area Resistance
Use a two-compartment cell with the membrane clamped between, both sides filled with 0.5 M NaCl. Measure cell resistance with and without the membrane (AC measurement or current-interrupt preferred; a basic LCR meter at 1 kHz works). Area resistance = (R_with - R_without) x exposed area.

### Permselectivity (membrane potential method)
Place 0.1 M KCl and 0.5 M KCl on opposite sides of the membrane. Measure open-circuit voltage with two identical reference electrodes (Ag/AgCl). Apparent permselectivity = measured voltage / theoretical Nernst voltage (about 36.9 mV at 25 C for this pair) x 100.

### Durability
Record the longest continuous exposure to your working solution (note pH, oxidizer presence) and describe any degradation.

## Rules

- Add rows only. Never edit or delete existing rows; corrections get a new row with a note.
- Empty cells are fine. Partial data beats no data.
- Use the exact units in the headers.
