# Community Builds

Independent replications of the open-source ion exchange membrane. Every entry links to public evidence published by the builder, not by Rowow LLC. The same records are kept in machine-readable form in [`data/replications.csv`](data/replications.csv).

**Verified independent replications: 3** (as of 2026-11-03)

Three builders with no financial or employment tie to Rowow LLC fabricated the membrane from the published recipe on camera and then ran it in an electrolysis cell. In each case the cell behaved as a cation exchange membrane should: acid formed at the anode side and base at the cathode side of a salt solution.

To get listed, open a [Build Report](../../issues/new?template=build-report.yml). Failed builds are listed too.

## Verified Builds

| # | Published | Builder | Membrane | Fabrication shown | Test shown | Evidence |
|---|-----------|---------|----------|-------------------|------------|----------|
| 1 | 2026-03-22 | PushingButtons ([@SciPushingButtons](https://www.youtube.com/@SciPushingButtons)) | Cation | Pool-filter cation exchange beads ground to powder, mixed about 50/50 by volume with clear PVC cement, applied to woven fiberglass, cured about two hours at room temperature | NaCl electrolysis across the membrane: anode side turned acidic, cathode side basic | [Replicating and Testing Rowow's Open Source Cation Exchange Membrane](https://www.youtube.com/watch?v=-_kMtNR8-Ck) |
| 2 | 2026-05-09 | Neptunium ([@Neptunium](https://www.youtube.com/@Neptunium)) | Cation | Cation exchange resin ground in a high-speed grinder, mixed with an equal volume of clear PVC cement, spread on a polypropylene sheet, dried about six hours | Salt water cell, graphite anode and stainless steel cathode: cathode side turned alkaline | [Possible breakthrough in electrochemistry](https://www.youtube.com/watch?v=ZRBlKU7zKr8) (build from about 0:55, test from about 2:24) |
| 3 | 2026-06-03 | NightHawkInLight ([@Nighthawkinlight](https://www.youtube.com/@Nighthawkinlight)) | Cation and anion | Resin ground in a high-speed grinder (anion resin with talc to stop clumping), mixed 50/50 by volume with PVC cement, cast as plain film and painted onto woven fiberglass | Multi-chamber salt electrolysis with pH indicator, plus acid, flow battery and hydrogen demonstrations built with the membranes | [Electricity Does Not "Split" H2O. And That's VERY Useful.](https://www.youtube.com/watch?v=eq7fR9ISuCw) (recipe credited at about 17:16, fabrication from about 18:20) |

### Follow-up work by the same builders

These are not separate replications. They extend builds 1 and 3 and are listed because they use the membrane in further experiments.

| Published | Builder | What was done | Evidence |
|-----------|---------|---------------|----------|
| 2026-04-12 | PushingButtons | Designed a 3D-printable membrane test cell (O-ring seals, headspace ports) and tested membranes with potassium carbonate and sodium acetate electrolytes, with gas analysis on both sides and a final pH check | [3D Printing Electrolysis Cells for Testing Rowow DIY Cation Exchange Membranes + Gas Analysis](https://www.youtube.com/watch?v=vHhBwo5S-PU) |
| 2026-05-15 | PushingButtons | Electrolysis of dissolved neodymium magnet in sulfuric acid across the membrane; neodymium absorbance on the cathode side rose, measured by UV-VIS. This shows concentration, not separation of neodymium from iron | [Using Rowow's Cation Exchange Membrane to Concentrate Neodymium Magnet Solution](https://www.youtube.com/watch?v=TID-_3gld_k) |
| 2026-06-05 | Hackaday (written coverage of build 3) | Article by Maya Posch on the NightHawkInLight video, crediting the Rowow membrane recipe | [Using Electrolysis For More Than Just Generating Hydrogen](https://hackaday.com/2026/06/05/using-electrolysis-for-more-than-just-generating-hydrogen/) |

## What Has Not Been Measured Independently

The three replications show that the recipe can be followed from public documentation and that the result passes cations and blocks anions in a working cell. None of them reports ion exchange capacity, area resistance, permselectivity, or durability over weeks of service. Those numbers are the next gap in the public record. If you can measure any of them, add a row to [`data/membrane_characterization.csv`](data/membrane_characterization.csv) following [`data/README.md`](data/README.md).

## Reported, Pending Verification

Builds mentioned in Discord, YouTube comments, or forks that have no public fabrication evidence yet. If one of these is you, file a Build Report and it moves up to the verified table.

| Date noticed | Source | Notes |
|--------------|--------|-------|
| | | |

## What Counts as Verified

A build is verified when the builder has published evidence (photos, video, or measured data) showing the membrane was fabricated from the open-source recipe by someone other than Rowow LLC. A build shown working in a cell is listed as tested; a build shown only as fabricated is listed as fabricated. Failed builds are listed when reported, because they document the process as much as successes do.

Entries made from public videos, without a Build Report from the builder, say so in `data/replications.csv`. Builders can ask for any entry to be corrected or removed by opening an issue.

## Why This Page Exists

Independent replication is the strongest evidence that an open hardware process works as documented. This log is the public record of who has done it and where to see it.
