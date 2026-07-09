# Farm Project - Claude Skills Documentation

This directory contains 9 specialized AI skills designed to help you evaluate land, design permaculture farms, and implement your farm project in Portugal (and future expansion to Spain, Brazil, and other countries).

## Skills Overview

### 1. Country Legal Analyst
**Purpose**: Interpret land-use regulations, building rights, and agricultural licensing

**Use when you need to**:
- Understand PDM classifications and zoning
- Determine if you can build on a property
- Check protected area restrictions (REN, RAN, Natura 2000)
- Verify water rights
- Understand agricultural and processing licensing
- Navigate bureaucracy in Portugal, Spain, or Brazil

**Key outputs**:
- Legal status summary
- Building pathway identification
- Required permits and licenses
- Verification checklist
- Confidence assessment (what's confirmed vs. uncertain)

---

### 2. Climate & Soil Analyst
**Purpose**: Assess environmental conditions and match them to appropriate farming activities

**Use when you need to**:
- Evaluate climate suitability for specific crops or animals
- Assess soil quality and limitations
- Determine water availability and needs
- Score enterprises based on environmental fit
- Create soil improvement strategies

**Key outputs**:
- Climate profile (temperature, rainfall, frost, growing season)
- Soil profile (texture, depth, pH, drainage, fertility)
- Water assessment (sources, reliability, irrigation needs)
- Enterprise suitability matrix (0-5 scores)
- Improvement recommendations

---

### 3. Permaculture Designer
**Purpose**: Create integrated farm designs using permaculture principles

**Use when you need to**:
- Design zone-based layouts (Zone 0-5)
- Plan water harvesting systems (swales, ponds, tanks)
- Create sector maps (sun, wind, fire, water, access)
- Design functional stacking and integration
- Sequence plantings and development

**Key outputs**:
- Zone design (daily use → wild areas)
- Sector analysis (external energies)
- Water management design
- Soil fertility cycling plan
- Integration strategies (chickens + orchards, goats + woodland, etc.)
- Phased planting plan

---

### 4. Enterprise Planner
**Purpose**: Compare farming activities and recommend the best enterprise mix

**Use when you need to**:
- Score enterprises across 11 criteria (climate, soil, water, legal, ROI, etc.)
- Rank activities by timeline (fast/medium/long-term returns)
- Identify synergies and conflicts
- Balance self-sufficiency with income goals
- Create diversified enterprise portfolios

**Key outputs**:
- Enterprise comparison table (scored 0-5 across 11 criteria)
- Ranked recommendations (Tier 1-4)
- Synergy matrix (what works well together)
- Timeline-based enterprise mix
- Labor calendar
- Risk assessment by enterprise

---

### 5. Land Evaluator
**Purpose**: Produce comprehensive land evaluations with buy/maybe/reject recommendations

**Use when you need to**:
- Evaluate a property you're considering purchasing
- Score a parcel across 8 weighted categories (100 points total)
- Identify critical unknowns before purchase
- Estimate development costs
- Get a clear recommendation

**Key outputs**:
- 100-point scorecard
- Buy/Maybe/Reject recommendation
- Detailed analysis (legal, environmental, enterprises, permaculture potential)
- Critical unknowns checklist (what to verify before buying)
- Development cost estimate
- SWOT analysis

---

### 6. Financial Planner
**Purpose**: Assess economic viability and project cash flows

**Use when you need to**:
- Estimate total investment required (CAPEX)
- Calculate annual operating costs (OPEX)
- Project revenue by year and enterprise
- Determine payback period
- Assess financial viability for your family
- Value self-sufficiency production

**Key outputs**:
- CAPEX breakdown (land, infrastructure, enterprise startup)
- OPEX breakdown (annual costs by category)
- Revenue projections (Year 1, 3, 5, 10)
- Self-sufficiency value (household food/fuel/fiber production)
- Cash flow projection (10-year horizon)
- Break-even analysis
- Risk assessment
- Funding strategy (personal capital, loans, grants)

---

### 7. Phased Implementation Planner
**Purpose**: Convert strategy into actionable, sequenced implementation plans

**Use when you need to**:
- Break farm development into logical phases (0-6mo, 6-24mo, 2-5yr, 5-10yr)
- Sequence activities logically (water before irrigation, fencing before animals)
- Balance observation with action
- Manage cash flow through phased investment
- Avoid overwhelm by staging complexity

**Key outputs**:
- Phase 0: Pre-purchase verification checklist
- Phase 1 (Months 0-6): Observation & quick wins
- Phase 2 (Months 6-24): Foundation systems
- Phase 3 (Years 2-5): Production & diversification
- Phase 4 (Years 5-10+): Maturity & optimization
- Seasonal timing guidance
- Budget by phase

---

### 8. Market Researcher
**Purpose**: Fetch real Portuguese farmer/producer data from reformaagraria.pt — prices, products, contacts, locations

**Use when you need to**:
- Find actual market prices for products in your region
- Identify competitors and their pricing
- Discover producers to visit or learn from
- Validate revenue projections with real data
- Find market gaps (products with no local suppliers)

**Key outputs**:
- Price tables with regional breakdowns
- Competitor analysis matrix
- Producer contact information
- Farm visit recommendations
- Market gap identification

---

### 9. Knowledge Base Manager
**Purpose**: Maintain and expand the modular farm decision-support system

**Use when you need to**:
- Add a new country module (Spain, Brazil, etc.)
- Create or update enterprise profiles
- Document lessons learned from land evaluations
- Track sources and verify information
- Ensure modularity and reusability

**Key outputs**:
- Structured country modules
- Consistent enterprise database
- Source documentation
- Lessons learned database
- Update logs and confidence assessments

---

## How to Use These Skills

### For Evaluating a Specific Property

**Step-by-step workflow**:

1. **Country Legal Analyst**: Check legal status, PDM, building rights, protected areas
2. **Climate & Soil Analyst**: Assess environmental conditions and enterprise fit
3. **Enterprise Planner**: Recommend activities suited to the land and your goals
4. **Permaculture Designer**: Create conceptual integrated design
5. **Land Evaluator**: Integrate all analysis into 100-point scorecard and recommendation
6. **Financial Planner**: Assess economic viability and cash flow
7. **Phased Implementation Planner**: Create step-by-step development roadmap

Result: Comprehensive property evaluation with clear buy/maybe/reject decision

### For Designing Your Purchased Farm

**Step-by-step workflow**:

1. **Permaculture Designer**: Create zone and sector design
2. **Enterprise Planner**: Finalize enterprise mix based on confirmed conditions
3. **Phased Implementation Planner**: Create detailed 5-10 year implementation plan
4. **Financial Planner**: Refine financial projections and funding strategy

Result: Complete farm design and implementation roadmap

### For Building the Knowledge Base

**Ongoing workflow**:

1. **Knowledge Base Manager**: Add country modules (Spain, Brazil)
2. **Knowledge Base Manager**: Expand enterprise database (add new activities)
3. **Knowledge Base Manager**: Document lessons from land evaluations and implementations
4. **Knowledge Base Manager**: Update sources and verify information regularly

Result: Expanding, reusable decision-support system

---

## Skills Organization

All skills are stored in:
```
.claude/skills/
├── country-legal-analyst.md
├── climate-soil-analyst.md
├── permaculture-designer.md
├── enterprise-planner.md
├── land-evaluator.md
├── financial-planner.md
├── phased-implementation-planner.md
├── market-researcher.md
└── knowledge-base-manager.md
```

---

## Core Principles (Applies to All Skills)

### 1. Legal Feasibility First
Never assume a use is possible without verification. Always check:
- Land classification
- Building rights
- Protected areas
- Water rights
- Activity licensing

### 2. Environmental Fit
Match every activity to the land:
- Climate suitability
- Soil suitability
- Water availability
- Topography
- Microclimates

### 3. Permaculture Principles
Design for:
- Earth care, people care, fair share
- Observation before action
- Water capture and soil building
- Functional stacking and integration
- Diversity and resilience

### 4. Modularity and Portability
- Separate universal logic from country-specific rules
- Portugal, Spain, Brazil as separate modules
- Reusable templates and frameworks
- Consistent structure across all analysis

---

## Skill Integration

The skills work together:

```
Country Legal Analyst → provides legal constraints
        ↓
Climate & Soil Analyst → provides environmental conditions
        ↓
Enterprise Planner → matches activities to constraints + conditions
        ↓
Permaculture Designer → integrates activities into holistic design
        ↓
Land Evaluator → synthesizes into buy/reject recommendation
        ↓
Financial Planner → assesses economic viability
        ↓
Phased Implementation Planner → sequences development
        ↓
Knowledge Base Manager → captures lessons, improves system
```

---

## Quick Start Guide

### I want to evaluate a property listing

1. Gather information:
   - Location (municipality, coordinates)
   - Size (hectares)
   - Price
   - Photos/description
   - Existing buildings (if any)

2. Use skills in order:
   - **Country Legal Analyst**: "Analyze legal status for [property location], [size], [desired uses]"
   - **Climate & Soil Analyst**: "Assess environmental conditions for [location], [altitude], [soil description from listing]"
   - **Enterprise Planner**: "Recommend enterprises for [family size], [budget], [timeline], given [legal constraints] and [environmental conditions]"
   - **Land Evaluator**: "Evaluate this property and give buy/maybe/reject recommendation"

3. Result: Comprehensive evaluation report

### I purchased land and want to design my farm

1. Gather confirmed information:
   - Legal status (verified PDM, REN, RAN, water rights)
   - Environmental data (soil tests, water tests, climate data, topography)
   - Family resources (budget, labor, timeline, goals)

2. Use skills in order:
   - **Permaculture Designer**: "Design integrated farm for [property details], [family goals], [confirmed constraints]"
   - **Enterprise Planner**: "Create diversified enterprise plan for [design], [budget], [labor capacity]"
   - **Financial Planner**: "Project cash flow for [enterprises], [infrastructure needs], [family size]"
   - **Phased Implementation Planner**: "Create 5-year phased plan for [budget], [labor], [priorities]"

3. Result: Complete farm design and implementation roadmap

### I want to expand the system to Spain

1. Use **Knowledge Base Manager**:
   - "Create Spain country module using template"
   - "Research Spanish land categories and planning system"
   - "Document building pathways in Spain"
   - "Add Spanish regulations to enterprise database"

2. Result: Spain module ready for property evaluations

---

## Tips for Best Results

### Be Specific
- Provide actual data (measurements, prices, dates, quantities)
- Name the municipality, not just "Portugal"
- Share real constraints, not ideal scenarios

### Follow the Sequence
- Legal first (no point designing if you can't build)
- Environment second (climate and soil determine what's possible)
- Enterprises third (match activities to constraints)
- Design fourth (integrate activities)
- Financial fifth (assess viability)
- Phasing last (sequence implementation)

### Request Conservative Estimates
- Ask for realistic, not optimistic projections
- Overestimate costs, underestimate revenues
- Include contingencies and learning curves

### Verify Critical Assumptions
- Legal status (never assume - always verify with câmara municipal)
- Water sources (test flow and quality)
- Soil conditions (soil tests, not photos)
- Market prices (local research, not internet averages)

### Iterate and Refine
- Start with broad assessment
- Refine with more data
- Adjust plans based on observation
- Update financial projections with actual results

---

## Expected Outputs by Skill

Each skill produces structured, actionable outputs:

| Skill | Main Output Format | Typical Length |
|-------|-------------------|----------------|
| Country Legal Analyst | Legal analysis report | 3-8 pages |
| Climate & Soil Analyst | Environmental profile + suitability matrix | 4-10 pages |
| Permaculture Designer | Zone/sector design + integration plan | 6-15 pages |
| Enterprise Planner | Comparison table + recommendations | 5-12 pages |
| Land Evaluator | 100-point scorecard + full report | 10-20 pages |
| Financial Planner | Cash flow projections + viability assessment | 8-15 pages |
| Phased Implementation Planner | 4-phase roadmap with budgets | 6-12 pages |
| Knowledge Base Manager | Module updates + documentation | Variable |

---

## Continuous Improvement

The Farm Project system improves with use:

1. **Every land evaluation** → Lessons learned → Better future evaluations
2. **Every farm design** → Design patterns → Better future designs
3. **Every implementation** → Reality checks → Better cost/timeline estimates
4. **Every country added** → Refined templates → Easier future expansion

Use the **Knowledge Base Manager** to capture these learnings and improve the system over time.

---

## Support and Resources

### Official Sources (Portugal)
- PDM: Municipal planning office websites
- REN/RAN: ICNF and APA websites
- Land registry: Conservatória do Registo Predial
- Agricultural licensing: DGAV
- Grants: PDR 2020 (or current program)

### Official Sources (Spain)
- Varies by autonomous community
- Consult regional planning authorities

### Official Sources (Brazil)
- CAR: Sistema Nacional de Cadastro Ambiental Rural
- Agricultural licensing: State-level Secretarias de Agricultura

### Further Development
As you use the system:
- Document new enterprises (add to database)
- Refine economic estimates (actual vs. projected)
- Expand country modules (Spain, Brazil details)
- Create case studies (successful farm examples)
- Build design pattern library (proven integrations)

---

## Questions or Issues?

If a skill produces unclear outputs or you need additional functionality:

1. Provide more specific input data
2. Request clarification on specific sections
3. Ask for examples or case studies
4. Request format adjustments for your needs

The skills are designed to be comprehensive but flexible. Adapt them to your specific situation while maintaining the core structure and principles.

---

**Remember**: These skills are tools to support your decision-making, not to replace professional verification (lawyers, architects, engineers, agronomists). Always verify critical legal and technical information with qualified professionals before making major commitments.

**Good luck with your Farm Project!** 🌱🐓🌳
