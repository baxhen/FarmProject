
# Farm Project — Modular Guidelines for Land Evaluation, Permaculture Design, and Farm Skills

**Version:** 0.2  
**Initial focus:** Miranda do Douro, Bragança, Portugal  
**Future use:** Portugal, Spain, Brazil, and other countries  
**Core purpose:** Build a modular decision-support system for evaluating land, understanding legal constraints, designing productive farms, and choosing activities adapted to soil, climate, water, law, and market conditions.

---

## 1. Project Mission

The Farm Project is not only a Portugal farm-planning project. It should be designed as a reusable framework that can later be adapted to other countries or sold as a consulting/AI skill system.

The first implementation is Portugal, especially Miranda do Douro. However, the system must separate universal farm-design logic from local legal rules.

The project should help answer:

- What can legally be done on a specific parcel of land?
- What can be built, renovated, licensed, or operated?
- What activities fit the soil, climate, water, and legal restrictions?
- Which activities support family self-sufficiency?
- Which activities can generate income?
- Which activities give fast returns while long-term systems mature?
- How should the land be developed using permaculture principles?
- Could the same system be adapted to Spain, Brazil, or another country?

---

## 2. Core Principles

### 2.1 Legal feasibility first

Never assume a use is possible from photos, seller descriptions, or the word “quinta,” “farm,” “finca,” or “sítio.”

Always verify:

- Land classification.
- Building rights.
- Protected area restrictions.
- Water rights.
- Agricultural licensing.
- Residential permission.
- Food-processing rules.
- Livestock rules.
- Tourism rules.
- Municipal interpretation.

### 2.2 Environmental fit

Every activity must be matched to the land.

Evaluate:

- Temperature.
- Frost.
- Heat waves.
- Rainfall.
- Drought.
- Wind.
- Solar exposure.
- Altitude.
- Slope.
- Soil texture.
- Soil depth.
- Soil pH.
- Organic matter.
- Drainage.
- Rockiness.
- Water availability.
- Existing vegetation.
- Fire risk.

### 2.3 Permaculture as the land-development philosophy

The project should generally follow permaculture principles, especially for self-sufficiency, resilience, and long-term regeneration.

Use these ethics:

1. Earth care.
2. People care.
3. Fair share / reinvest surplus.

Use these practical principles:

- Observe before making permanent changes.
- Design from patterns to details.
- Capture and store water.
- Build soil fertility.
- Stack functions.
- Use biological diversity.
- Integrate animals, plants, water, compost, trees, and buildings.
- Turn waste streams into resources.
- Prefer perennial and regenerative systems where practical.
- Start small, test, and scale.
- Use zones according to frequency of use.
- Use sectors for sun, wind, fire, water flow, road access, and views.
- Prefer resilient systems over maximum short-term production.

### 2.4 Modularity and portability

The system must be modular.

Portugal should be one country module, not the entire project.

```text
Farm Project Core
│
├── Universal Land Evaluation Module
├── Universal Climate and Soil Module
├── Universal Water Module
├── Universal Enterprise Database
├── Universal Permaculture Design Module
├── Universal Financial Model
├── Universal Risk Model
│
├── Country Module: Portugal
├── Country Module: Spain
├── Country Module: Brazil
└── Future Country Modules
```

---

## 3. Core Universal Modules

These modules should work in any country.

| Module | Purpose |
|---|---|
| Legal Module | Identify the applicable laws, zoning, building limits, and licensing pathways. |
| Climate Module | Determine temperature, frost, rainfall, drought, heat, and growing-season constraints. |
| Soil Module | Determine fertility, pH, depth, drainage, structure, erosion risk, and improvement strategy. |
| Water Module | Determine water availability, storage potential, irrigation limits, and carrying capacity. |
| Enterprise Module | Compare crops, animals, forestry, processing, tourism, and other activities. |
| Permaculture Module | Design integrated systems using zones, sectors, water, soil, trees, animals, and energy flows. |
| Infrastructure Module | Plan buildings, access, fencing, electricity, roads, storage, processing, and utilities. |
| Financial Module | Estimate investment, operating costs, payback, cash flow, and family-support potential. |
| Risk Module | Identify legal, environmental, market, disease, fire, water, and labour risks. |
| Implementation Module | Convert the strategy into phased development: 0–6 months, 6–24 months, 2–5 years, 5+ years. |

---

## 4. Country Module Template

Every country should have its own module.

```markdown
# Country Module: [Country]

## 1. Land Categories
- Rural land:
- Urban land:
- Developable land:
- Agricultural reserve:
- Ecological reserve:
- Forest categories:
- Protected areas:

## 2. Planning Authorities
- National:
- Regional/state:
- Municipal:
- Agricultural:
- Environmental:
- Water:
- Food safety:
- Tourism:

## 3. Building Pathways
- Normal dwelling:
- Farmer dwelling:
- Existing building renovation:
- Agricultural warehouse:
- Livestock building:
- Greenhouse:
- Processing facility:
- Rural tourism:
- Temporary/mobile structures:

## 4. Water Rules
- Wells:
- Boreholes:
- Springs:
- Streams:
- Irrigation:
- Rainwater harvesting:
- Reservoirs:

## 5. Farm Activity Rules
- Crops:
- Livestock:
- Forestry:
- Food processing:
- Dairy:
- Meat:
- Eggs:
- Honey:
- Mushrooms:
- On-farm sales:
- Tourism:

## 6. Funding and Grants
- Agricultural grants:
- Young farmer programs:
- Regenerative agriculture:
- Water infrastructure:
- Rural tourism:
- Renewable energy:

## 7. Official Sources
- Land planning:
- Agriculture:
- Environment:
- Water:
- Food safety:
- Tax/business:
```

---

## 5. Portugal Module — Initial Implementation

### 5.1 Key Portuguese concepts

Research and maintain:

- PDM — Plano Diretor Municipal.
- Solo rústico.
- Solo urbano.
- Solo urbanizável, if used in the relevant plan.
- REN — Reserva Ecológica Nacional.
- RAN — Reserva Agrícola Nacional.
- Natura 2000.
- ICNF protected areas.
- Parque Natural do Douro Internacional.
- Fire-risk rules.
- Water-domain restrictions.
- Caderneta predial.
- Artigo matricial.
- Registo predial.
- Licenciamento.
- Comunicação prévia.
- Pedido de Informação Prévia (PIP).

### 5.2 Portugal land-check workflow

For every Portuguese parcel:

1. Identify the exact parcel.
2. Collect caderneta predial, artigo matricial, registry data, boundaries, coordinates, and access.
3. Check the PDM.
4. Check Planta de Ordenamento.
5. Check Planta de Condicionantes.
6. Check REN.
7. Check RAN.
8. Check Natura 2000 and protected areas.
9. Check fire-risk restrictions.
10. Check water restrictions.
11. Confirm existing buildings are legally registered.
12. Separate agricultural use from construction use.
13. Confirm uncertain points with the Câmara Municipal.
14. Consider a PIP before purchase if building rights matter.

### 5.3 Portugal building pathways to research

- Existing registered dwelling.
- Renovation of legal building or ruin.
- Habitação do agricultor / farmer dwelling.
- Armazém agrícola / agricultural warehouse.
- Livestock shelter.
- Greenhouse.
- Processing building.
- Farm operations centre.
- Agro-tourism / rural tourism.

Important rule:

> Do not assume an agricultural building can be used as a permanent house unless the licensed use allows it.

---

## 6. Spain Module — Future Extension

Spain must be treated as a separate legal system.

Research:

- Suelo urbano.
- Suelo urbanizable.
- Suelo rústico / no urbanizable.
- Autonomous community rules.
- Municipal planning.
- Rural housing rights.
- Agricultural building rights.
- Water rights.
- Environmental restrictions.
- Livestock rules.
- Food-processing rules.
- Rural tourism rules.
- Grants and subsidies.

Spain is not uniform. Autonomous community rules may be decisive.

---

## 7. Brazil Module — Future Extension

Brazil must be treated as a separate legal and environmental system.

Research:

- Rural property classification.
- Municipal zoning.
- CAR — Cadastro Ambiental Rural.
- APP — Área de Preservação Permanente.
- Reserva Legal.
- Environmental licensing.
- Water use rights.
- Land-title risks.
- Deforestation restrictions.
- State-level rules.
- Agroforestry legality.
- Rural credit.
- Food-processing rules.
- Livestock rules.
- Tourism rules.

Brazil requires strong environmental and land-title due diligence.

---

## 8. Climate and Soil Module

The climate and soil module should determine what activities are realistic and what design interventions are needed.

### 8.1 Climate data to collect

For every region or parcel:

- Average annual temperature.
- Average monthly temperatures.
- Summer maximums.
- Winter minimums.
- Frost dates.
- Number of frost days.
- Growing season length.
- Chill hours.
- Heat waves.
- Rainfall by month.
- Drought frequency.
- Snow or hail risk.
- Wind direction and intensity.
- Solar radiation.
- Altitude.
- Aspect and slope orientation.
- Microclimates.

### 8.2 Soil data to collect

For every parcel:

- Texture: sand, silt, clay, loam.
- Soil depth.
- Rockiness.
- pH.
- Organic matter.
- Drainage.
- Compaction.
- Water-holding capacity.
- Fertility.
- Salinity.
- Erosion risk.
- Contamination risk.
- Existing vegetation indicators.
- Soil biology.

### 8.3 Soil-to-activity matching

| Soil condition | Suitable activities | Improvement strategy |
|---|---|---|
| Deep fertile loam | Vegetables, orchards, berries, poultry, intensive gardens | Compost, mulch, cover crops |
| Clay soil | Pasture, ponds, some tree crops, ducks | Organic matter, drainage, deep-rooted plants |
| Sandy soil | Herbs, asparagus, poultry, drought-tolerant crops | Compost, biochar, mulch, windbreaks |
| Rocky shallow soil | Goats, sheep, olives, almonds, figs, herbs, beekeeping | Terracing, tree pockets, grazing control |
| Acidic soil | Chestnuts, berries, forestry | Organic matter, lime if appropriate |
| Alkaline soil | Olives, almonds, grapes, figs, aromatic herbs | Species selection, compost |
| Erosion-prone slope | Agroforestry, silvopasture, contour orchards | Swales, terraces, permanent groundcover |
| Humid shaded soil | Mushrooms, berries, chestnuts, woodland systems | Drainage, airflow, shade management |
| Dry poor soil | Sheep, goats, olives, almonds, carob, herbs | Water harvesting, mulch, drought-tolerant perennials |

### 8.4 Climate-to-activity matching

| Climate condition | Suitable activities | Main risks |
|---|---|---|
| Cold winters | Chestnuts, walnuts, apples, pears, hardy livestock | Frost, short growing season |
| Hot dry summers | Olives, figs, almonds, grapes, sheep, goats, herbs | Drought, fire, irrigation demand |
| Humid mild climate | Mushrooms, berries, pasture, vegetables, dairy | Fungal disease, weed pressure |
| High altitude | Hardy trees, grazing, forestry, berries | Wind, snow, late frost |
| Low rainfall | Dryland perennials, grazing, cereals, aromatic herbs | Low carrying capacity |
| Strong wind | Sheep, forestry, hardy trees, windbreak systems | Evaporation, tree damage |
| Long growing season | Vegetables, poultry, orchards, multiple crop cycles | Pest pressure, irrigation demand |

### 8.5 Enterprise compatibility scoring

Every enterprise should be scored 0–5 for:

- Climate suitability.
- Soil suitability.
- Water suitability.
- Legal simplicity.
- Infrastructure requirement.
- Labour demand.
- Fast-return potential.
- Long-term value.
- Self-sufficiency value.
- Market potential.
- Permaculture synergy.

---

## 9. Permaculture Design Module

### 9.1 Zone planning

Use zones to organize the farm by frequency of use.

| Zone | Description | Examples |
|---|---|---|
| Zone 0 | Home / operations centre | House, kitchen, office, energy systems |
| Zone 1 | Daily-use intensive area | Kitchen garden, herbs, nursery, chickens, compost |
| Zone 2 | Frequent-use productive area | Orchards, berries, rabbits, ducks, greenhouse |
| Zone 3 | Field-scale production | Grains, pasture, sheep, goats, larger orchards |
| Zone 4 | Managed semi-wild area | Woodland, firewood, forage, mushroom logs |
| Zone 5 | Wild observation area | Biodiversity, wildlife, ecological reserve |

### 9.2 Sector planning

Map external forces:

- Sun.
- Wind.
- Fire.
- Water flow.
- Cold air drainage.
- Road access.
- Noise.
- Views.
- Wildlife.
- Neighbouring land uses.

### 9.3 Water design

Prioritize:

1. Reduce water demand.
2. Slow water runoff.
3. Increase infiltration.
4. Store water in soil.
5. Store water in ponds, tanks, cisterns, or reservoirs where legal.
6. Reuse greywater where legal.
7. Match crops and animals to realistic water availability.

Possible design elements:

- Swales.
- Terraces.
- Keyline-style ripping where appropriate.
- Mulch basins.
- Ponds.
- Roof-water harvesting.
- Drip irrigation.
- Tree belts.
- Windbreaks.
- Soil organic matter increase.

### 9.4 Soil fertility design

Build fertility through:

- Compost.
- Animal manure.
- Rotational grazing.
- Cover crops.
- Mulching.
- Biochar where appropriate.
- Leaf litter.
- Green manures.
- Agroforestry prunings.
- Mushroom substrate reuse.
- Worm systems.
- Reduced tillage.

### 9.5 Functional stacking

Prefer elements that perform multiple functions.

Examples:

| Element | Functions |
|---|---|
| Chickens | Eggs, meat, pest control, manure, compost turning |
| Goats | Milk/meat, brush clearing, manure, fire-risk reduction |
| Mulberry trees | Silkworm feed, fruit, shade, animal fodder, biomass |
| Chestnut trees | Food, timber, shade, wildlife, long-term value |
| Pond | Irrigation, ducks, fish, microclimate, fire reserve |
| Mushroom area | Food, income, waste recycling, shade use |
| Hedgerow | Windbreak, biodiversity, forage, privacy, pollination |
| Compost system | Fertility, waste cycling, heat, nursery inputs |

---

## 10. Enterprise Database Template

Each enterprise should be documented using the same structure.

```markdown
# Enterprise: [Name]

## 1. Description
What is produced?

## 2. Legal Requirements
Country:
Region:
Municipality:
Licenses:
Animal/food/water/building rules:

## 3. Environmental Fit
Climate:
Soil:
Water:
Shade:
Slope:
Temperature limits:

## 4. Infrastructure
Buildings:
Fencing:
Water:
Electricity:
Equipment:
Storage:
Processing:

## 5. Economics
Startup cost:
Operating cost:
Time to first income:
Time to profitability:
Revenue potential:
Market channels:

## 6. Labour
Daily labour:
Seasonal labour:
Skill level:
Family suitability:

## 7. Self-Sufficiency Value
Food:
Fertility:
Fuel:
Fibre:
Animal feed:
Household use:

## 8. Permaculture Synergies
Inputs from other systems:
Outputs to other systems:
Waste reuse:
Stacked functions:

## 9. Risks
Legal:
Disease:
Climate:
Market:
Predators:
Labour:
Water:

## 10. Score
Climate:
Soil:
Water:
Legal:
ROI:
Self-sufficiency:
Permaculture synergy:
Overall:
```

---

## 11. Initial Enterprise Categories

### 11.1 Fast-return / learning enterprises

- Eggs.
- Chickens where legal and practical.
- Rabbits.
- Seasonal vegetables.
- Herbs.
- Nursery plants.
- Microgreens if market exists.
- Basic mushroom production using bought substrate.
- Compost products if permitted.
- Small-scale honey if training and conditions are adequate.

### 11.2 Medium-term enterprises

- Goats.
- Sheep.
- Berries.
- Beekeeping.
- Outdoor mushroom logs.
- Orchard establishment.
- Preserves.
- Dried herbs.
- Direct sales.
- Small-scale agroforestry products.

### 11.3 Long-term / infrastructure-heavy enterprises

- Cattle.
- Large nut orchards.
- Chestnut systems.
- Sericulture at scale.
- Rural tourism.
- Dairy and cheese production.
- On-farm processing kitchen.
- Timber systems.
- Large irrigation works.

### 11.4 Special research track: sericulture

Important clarification:

> Silkworms feed on mulberry leaves, especially Morus species, not blackberry bushes.

Research:

- Morus alba and Morus nigra.
- Leaf yield per hectare.
- Establishment time.
- Irrigation need.
- Labour intensity.
- Cocoon processing.
- Silk buyers.
- Value-added products.
- Integration with poultry, goats, shade, and agroforestry.

### 11.5 Special research track: mushrooms

Separate:

- Indoor controlled production.
- Outdoor log cultivation.
- Low-tech shaded production.
- Use of agricultural waste as substrate.
- Value-added mushroom products.

Research:

- Temperature and humidity requirements.
- Building legality.
- Energy demand.
- Cooling demand.
- Food-safety rules.
- Market demand.
- Integration with forestry and compost systems.

---

## 12. Land Evaluation Scorecard

Every parcel should be scored out of 100.

| Category | Points |
|---|---:|
| Legal viability | 20 |
| Water resources | 15 |
| Soil quality | 15 |
| Climate suitability | 10 |
| Existing buildings / building potential | 10 |
| Infrastructure and access | 10 |
| Enterprise compatibility | 10 |
| Permaculture design potential | 5 |
| Expansion potential | 5 |

### 12.1 Required outputs for every parcel

For each land listing or parcel, produce:

- Executive summary.
- Legal status.
- PDM/zoning interpretation.
- Protected-area constraints.
- Water assessment.
- Soil assessment.
- Climate assessment.
- Existing building assessment.
- Suitable enterprise ranking.
- Unsuitable or risky activities.
- Permaculture design opportunities.
- Estimated development cost.
- Development phases.
- Unknowns to verify before purchase.
- Overall score.
- Buy / maybe / reject recommendation.

---

## 13. Phased Development Model

### Phase 0 — Before purchase

- Legal due diligence.
- PDM check.
- Water verification.
- Soil and climate screening.
- Access and infrastructure check.
- Building legality check.
- Market access check.
- Initial enterprise compatibility.
- Purchase-risk decision.

### Phase 1 — First 0–6 months

- Observation period.
- Mapping.
- Soil tests.
- Water tests.
- Temporary fencing.
- Compost system.
- Kitchen garden.
- Small poultry trial.
- Basic tool storage.
- Fire-risk reduction.
- Relationship with municipality and neighbours.

### Phase 2 — 6–24 months

- Water harvesting.
- Irrigation system.
- Orchard establishment.
- Mulberry trial.
- Mushroom trial.
- Rabbit or poultry expansion.
- Rotational grazing trial.
- Nursery.
- Small direct-sales channels.
- Legal pathway for buildings.

### Phase 3 — 2–5 years

- Farm operations centre.
- Larger orchard/agroforestry.
- Goats or sheep.
- Processing facilities if legal.
- Tourism feasibility.
- Larger mushroom or sericulture system.
- Renewable energy.
- Storage and cold chain.

### Phase 4 — 5+ years

- Mature agroforestry.
- Family-scale food system.
- Multiple revenue streams.
- Possible rural tourism.
- Processing and value-added products.
- Education/workshops.
- Replicable consulting model.

---

## 14. Claude / AI Skill Specifications

These are modular “skills” that can be turned into Claude project instructions, custom GPT instructions, or independent consulting workflows.

### Skill 1 — Country Legal Analyst

**Purpose:** Explain the land-use and farm-building rules for a specific country.

**Inputs:**

- Country.
- Region/state.
- Municipality.
- Parcel information if available.
- Desired activities.
- Desired buildings.

**Outputs:**

- Legal land categories.
- Authorities involved.
- Building pathways.
- Protected-area risks.
- Water restrictions.
- Required permits.
- Official sources to check.
- Uncertainties.

**Rules:**

- Prefer official sources.
- Separate confirmed law from interpretation.
- Do not assume buildability.
- Flag when a local lawyer, architect, engineer, or municipality must confirm.

---

### Skill 2 — Municipal/PDM Analyst

**Purpose:** Interpret local planning rules for a specific municipality.

**Inputs:**

- Municipality.
- Parcel location.
- PDM category or zoning map.
- Desired use.
- Existing buildings.

**Outputs:**

- PDM category explanation.
- Allowed uses.
- Restricted uses.
- Building potential.
- Conditions and thresholds.
- Questions for the Câmara / municipality.
- Recommendation: proceed, investigate, or reject.

---

### Skill 3 — Climate and Soil Analyst

**Purpose:** Determine what the land can realistically support.

**Inputs:**

- Location.
- Altitude.
- Slope.
- Soil test.
- Soil map.
- Climate data.
- Water data.
- Existing vegetation.

**Outputs:**

- Climate profile.
- Soil profile.
- Main limitations.
- Best-fit activities.
- Activities to avoid.
- Soil improvement plan.
- Water strategy.
- Enterprise suitability matrix.

---

### Skill 4 — Permaculture Designer

**Purpose:** Convert parcel conditions into an integrated land design.

**Inputs:**

- Map.
- Slope.
- Water flows.
- Access.
- Buildings.
- Sun/wind/fire sectors.
- Soil zones.
- Desired activities.
- Family needs.

**Outputs:**

- Zone map concept.
- Sector analysis.
- Water-harvesting plan.
- Soil-building plan.
- Animal integration plan.
- Tree/agroforestry plan.
- Infrastructure placement logic.
- Phased implementation.

**Rules:**

- Observe before major intervention.
- Prioritize water, soil, access, fire resilience, and daily labour efficiency.
- Stack functions.
- Avoid designs that depend on unrealistic labour.

---

### Skill 5 — Enterprise Planner

**Purpose:** Compare possible farm activities and recommend the best mix.

**Inputs:**

- Land size.
- Climate.
- Soil.
- Water.
- Legal restrictions.
- Budget.
- Labour.
- Market access.
- Self-sufficiency goals.

**Outputs:**

- Ranked enterprise list.
- Fast-return options.
- Medium-term options.
- Long-term options.
- Synergies.
- Conflicts.
- Infrastructure needs.
- Legal complexity.
- Estimated ROI category.

---

### Skill 6 — Land Evaluator

**Purpose:** Produce a full parcel evaluation report.

**Inputs:**

- Land listing.
- Coordinates.
- Parcel documents.
- Photos.
- PDM data.
- Soil/climate/water data.
- Buyer goals.

**Outputs:**

- 100-point score.
- Buy/maybe/reject recommendation.
- Legal analysis.
- Environmental analysis.
- Enterprise compatibility.
- Permaculture potential.
- Cost estimate.
- Development roadmap.
- Critical unknowns.

---

### Skill 7 — Financial Planner

**Purpose:** Estimate whether the farm can become economically viable.

**Inputs:**

- Purchase price.
- Infrastructure needs.
- Enterprise choices.
- Family size.
- Cash reserve.
- Grant opportunities.
- Market assumptions.

**Outputs:**

- CAPEX estimate.
- OPEX estimate.
- Revenue scenarios.
- Payback timeline.
- Cash-flow risk.
- Break-even analysis.
- Family self-sufficiency value.
- Funding/grant research needs.

---

### Skill 8 — Modular Knowledge Base Manager

**Purpose:** Keep the project reusable and expandable.

**Inputs:**

- New research.
- Parcel reports.
- Enterprise studies.
- Legal findings.
- Country modules.
- Lessons learned.

**Outputs:**

- Updated country modules.
- Updated enterprise database.
- Updated decision rules.
- Source list.
- Open questions.
- Reusable templates.

**Rules:**

- Keep universal rules separate from country-specific rules.
- Keep Portugal, Spain, Brazil, and future countries in separate modules.
- Use consistent templates.
- Mark outdated or unverified information.
- Preserve source citations.

---

## 15. Working Rules for AI Assistants

Any AI assistant helping with this project should follow these rules:

1. Always separate universal farming logic from country-specific legal rules.
2. Always identify the relevant country, region, and municipality.
3. Never assume a structure is legal just because it exists.
4. Never infer building rights from real-estate listing language.
5. Always evaluate legal, water, soil, climate, access, and market factors together.
6. Always include permaculture design implications.
7. Always flag unknowns.
8. Always prefer official legal and technical sources.
9. Always produce practical outputs: tables, checklists, templates, scorecards, and phased plans.
10. Always explain whether an activity is suitable for self-sufficiency, income, or both.
11. Always consider modular reuse for other countries.
12. Always update the knowledge base when new verified information is found.

---

## 16. File and Folder Structure Recommendation

Use this project structure:

```text
Farm_Project/
│
├── 00_Master_Guidelines/
│   └── Farm_Project_Modular_Guidelines.md
│
├── 01_Core_Modules/
│   ├── Legal_Module.md
│   ├── Climate_Module.md
│   ├── Soil_Module.md
│   ├── Water_Module.md
│   ├── Enterprise_Module.md
│   ├── Permaculture_Module.md
│   ├── Financial_Module.md
│   └── Risk_Module.md
│
├── 02_Country_Modules/
│   ├── Portugal/
│   ├── Spain/
│   ├── Brazil/
│   └── Future_Countries/
│
├── 03_Region_Modules/
│   └── Portugal_Miranda_do_Douro/
│
├── 04_Enterprise_Database/
│   ├── Chickens.md
│   ├── Goats.md
│   ├── Sheep.md
│   ├── Rabbits.md
│   ├── Mushrooms.md
│   ├── Sericulture.md
│   ├── Orchards.md
│   ├── Olives.md
│   └── Agroforestry.md
│
├── 05_Land_Parcel_Reports/
│   └── Parcel_Template.md
│
├── 06_Financial_Models/
│
├── 07_Maps_and_Data/
│
└── 08_Source_Library/
```

---

## 17. Immediate Next Steps

1. Create the Portugal country module in detail.
2. Create the Miranda do Douro municipal/PDM module.
3. Build the land parcel report template.
4. Build the enterprise database template.
5. Build the climate and soil scoring matrix.
6. Build the permaculture site-design checklist.
7. Build the first enterprise comparison table for:
   - chickens,
   - rabbits,
   - goats,
   - sheep,
   - mushrooms,
   - sericulture,
   - olives,
   - chestnuts,
   - almonds,
   - vegetables,
   - herbs,
   - beekeeping.
8. Build the first full land evaluation scorecard.

---

## 18. Key Strategic Direction

The Farm Project should evolve into a **Farm Decision Support System**.

The long-term system should not merely answer individual questions. It should accumulate knowledge and become better at making land-purchase and farm-design decisions over time.

Final decision logic:

```text
Legal permission
+ Climate suitability
+ Soil suitability
+ Water security
+ Permaculture design potential
+ Infrastructure feasibility
+ Labour realism
+ Financial viability
+ Family self-sufficiency value
= Land and enterprise recommendation
```
