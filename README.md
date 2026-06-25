# 🖥 GE-IT-Skills-portfolio
## 💭 ABOUT ME:
## Hi! I'm Shamsiyah Hayya P. Talbin
### Mananaging risks rather than avoiding them.
## Brand Identity Hex Codes
- #fdeed9
- #ffadc6
- #a98360
- #473a120
- #fdeed9

# 🌴 The Davao Gulf Eco-Logistics Prompt System
## A Localized AI Framework for the Davao Region
### 1. System Prompt Template (V3 - Final Optimized)
This is the core, reusable system prompt. Copy and paste this into your AI interface to generate hyper-localized, professional content for economic and social initiatives in Mindanao.
markdown
### ROLE
Act as a Senior Economic Development Advisor specializing in the Davao Region's inter-island logistics and community-based eco-tourism sectors.

### OBJECTIVE
Your task is to draft a 250-word strategic action brief addressing a specific operational challenge. The brief must propose a solution that balances economic viability with environmental sustainability, reflecting the unique cultural and geographic landscape of the Davao Gulf.

### GEOGRAPHIC & CULTURAL CONSTRAINTS (MANDATORY)
- **Focus Area:** You must base all analysis and recommendations on the specific context of the Davao Region (Davao del Sur, Davao del Norte, Davao Oriental, and the Island Garden City of Samal).
- **Infrastructure:** Reference only local infrastructure. This includes, but is not limited to, the Davao-Samal Bridge project, the Sasa Wharf, the Pan-Philippine Highway (AH26), and local cold storage facilities in Digos or Tagum.
- **Stakeholders:** Explicitly mention collaboration with local stakeholders (e.g., the Samal Island Tourism Office, Davao del Norte Banana Growers Association, or the local Badjao communities).
- **Cultural Nuance:** Maintain a tone of *"Pakikipagkapwa-tao"* (shared identity and community spirit). Use professional but accessible language suitable for LGU officials and local cooperative leaders.

### STYLISTIC & FORMATTING RULES
- **Tone:** Authoritative yet collaborative. Data-driven but rooted in local community values.
- **Length:** Exactly 250 words.
- **Structure:** The response must be a single Markdown document with the following sections:
    - **` Situation Brief`** (A two-sentence summary of the challenge).
    - **` Strategic Recommendation`** (The core proposed action).
    - **` Localized Implementation Steps`** (A numbered list of 3 specific, actionable steps, each referencing a specific geographic location or local stakeholder).
    - **` Community & Environmental Impact Statement`** (One paragraph on social and ecological benefits).

### NEGATIVE CONSTRAINT (CRITICAL)
- **ABSOLUTELY FORBIDDEN:** Do not mention global supply chain theories, international trade indexes (e.g., WTO, IMF), or generic Western business models. The output must feel distinctly of and for Mindanao.
### 2. Prompt Battle Ledger This table demonstrates the iterative refinement process from a generic, ineffective prompt to the highly specialized V3 template above.
| Version | Prompt Modifier Added | Output Quality Reflection |
|--------|----------------------|---------------------------|
| V1 (Baseline) | “Create a plan to improve the local economy.” | Verdict: General and unusable. Output relied on generic concepts like digital transformation and global market integration, with no relevance to local LGU logistics or fisherfolk needs. |
| V2 (Role & Subject) | Added “Act as an economic advisor focusing on eco-tourism in Samal.” | Verdict: Slight improvement, but output relied on generic tourism models (e.g., Bali, Thailand), emphasized international tourism and luxury resorts, and ignored local ferry logistics and community-based tourism. |
| V3 (Final Optimized) | Added geographic constraints, cultural nuance (Pakikipagkapwa-tao), local stakeholders, strict word limit, and negative constraints. | Verdict: Target hit. Output was hyper-localized, actionable, referenced Davao–Samal infrastructure, involved local stakeholders, and used an LGU-appropriate, community-centered tone. |
### 3. Visual Branding Asset 
- Engine Used: DALL-E 3 (via ChatGPT Plus)
- Style: Flat Minimalist Vector
- Color Palette: Mindanao-inspired (Deep Forest Green #1E4A36, Earthy Brown #6B4A31, and Ocean Blue #2A5C73)
- The Visual Prompt (Used for Generation):
"A flat minimalist vector logo design. On the left, a stylized Philippine eagle's head, signifying the Davao Region. On the right, a shipping container truck interlocked with a durian fruit, representing agricultural logistics. The composition is enclosed in a clean geometric circle. The background is a very light, sandy beige. The style is clean, modern, corporate, with solid shapes and no gradients, suitable for a government social enterprise initiative."

# 📝 Literature Verification Log
## Topic: Renewable Energy Transition Challenges in Mindanao Grid Infrastructure
### 1. AI-Generated Summary Audit
I prompted an AI discovery tool (using a combination of Elicit, Semantic Scholar, and a custom GPT-4 instance) to synthesize recent literature (2020–2023) on the Mindanao energy mix, grid stability, and renewable energy transition. Below is the verification tracking matrix:
| AI-Generated Statement | Source Vetted Against | Status | Human Correction / Empirical Note |
|-----------------------|----------------------|--------|----------------------------------|
| “The Mindanao grid achieved 65% renewable energy penetration in 2024 due to massive solar expansions.” | MinDA 2024 Power Situationer Report | ❌ Flagged – Fabrication | **FALSE**. No 65% figure exists. Actual RE penetration as of Q1 2023 is ~38%, mainly from hydro (Agus–Pulangi). Solar and wind remain below 5%. |
| “The Agus-Pulangi hydropower complex supplies 80% of Mindanao's baseload power.” | NAPOCOR 2022 Annual Report | ⚠️ Flagged – Partially Inaccurate | **INACCURATE**. Actual contribution is ~55–60% of Mindanao’s baseload capacity, not 80%. |
| “A 2022 UP Mindanao study found geothermal potential in Davao del Sur could power 200,000 households by 2025.” | UP Mindanao Research Archive (2022) | ❌ Flagged – Fabrication | **FALSE**. No such study exists. A 2021 Mount Apo feasibility study exists but does not quantify household impacts. |
| “Coal-fired plants in Mindanao will be fully phased out by 2030 under the Philippine Energy Plan.” | DOE 2020–2040 Philippine Energy Plan | ⚠️ Flagged – Misinterpretation | **MISLEADING**. The plan sets a 35% national RE target by 2030 but does not mandate a coal phase-out in Mindanao. |
| “NGCP reported zero transmission curtailments in Mindanao for 2023.” | NGCP 2023 System Operations Report | ❌ Flagged – Fabrication | **FALSE**. At least three transmission curtailment events occurred in the Davao–Agusan corridor in 2023. |

### 2. Critical Reflection on Tool Limitations
| Limitation | Example from Audit | Mitigation Strategy |
|----------- |------------------ |---------------------|
| Hallucination of Statistics | AI invented a “65% renewable penetration” figure attributed to MinDA. | Always cross-check numerical claims against original PDFs or official data portals. |
| Citation Fabrication | AI cited a non-existent UP Mindanao 2022 study. | Verify every citation via Google Scholar, institutional repositories, or author records. |
| Temporal & Projection Confusion | AI mixed 2030 targets with 2023 actual data. | Check publication dates and clearly separate projections from current figures. |
| Western-Centric Baseline Bias | Assumed a solar-first transition model not aligned with Mindanao’s hydro-dominant grid. | Use local-context prompts grounded in Mindanao infrastructure (e.g., Agus–Pulangi). |
| Overconfidence in AI Summaries | Claims presented as facts with no uncertainty. | Require confidence scoring; low-confidence claims trigger mandatory human review. |                                           |

### 3. Recommended Human–AI Workflow

| Phase                          | Description                                                          |
| ------------------------------ | -------------------------------------------------------------------- |
| Phase 1 – AI Discovery         | AI summarizes 10–15 core documents and extracts all numerical claims |
| Phase 2 – Human Verification   | Verify citations, cross-check numbers, flag unverifiable claims      |
| Phase 3 – Bias & Context Check | Review for Western bias and missing local stakeholders               |
| Phase 4 – Final Synthesis      | Include only verified claims; annotate uncertainties                 |


# 📊 Data Analytics and Visual Report
## Dataset Focus: Davao Region Agricultural Production Index (Mock CSV Analysis)
### 1. Data Cleaning Protocol Log 
- Raw Input Problem: The CSV file contained multiple missing row cells for the year 2023 along with mixed numerical formatting styles (e.g., metric tons vs. kilograms vs. local unit "cavan" equivalents). Date formats were inconsistent (MM/DD/YYYY vs. DD/MM/YYYY), and three provinces had overlapping municipality names causing duplicate entries.
- AI Cleaning Instruction: "Scan this dataset. Identify all null rows in the 'Yield' column and replace them with the median value for that specific crop type within the same provincial cluster. Standardize all weight units to Metric Tons (MT). Parse all date columns into YYYY-MM-DD format. Remove duplicate rows based on composite key [Crop, Municipality, Year]."
- Result: Successfully normalized 120 row inputs across three provincial clusters (Davao del Norte, Davao del Sur, Davao Oriental). Imputed 47 missing yield values. Standardized 83 mixed-unit entries. Removed 12 duplicate rows. Flagged 8 outlier entries for manual review.

### 2. Visualizations Generated
(Embedded High-Contrast Bar Chart showing Cacao Production vs. Climate Outlier Years from 2020-2025)
| Year | Cacao Yield (MT)| Climate Event |
| -------- | -------- | -------- |
|2020      |1,200     | Normal   |
|2021      |1,350     |Mild La Niña
|2022      |2,200     |El Niño
|2023      |1,150     |Typhoon Odette
|2024      |1,400     |Recovery
|2025*     |2,100      |Projected 

2023 Provincial Crop Yield Comparison (Metric Tons)
| Province        | Cacao (MT)     | Banana (MT)        | Coconut (MT) |
| --------------- | -------------- | ------------------ | ------------ |
| Davao del Norte | ████████ 1,800 | ████████████ 2,500 | ██ 300       |
| Davao del Sur   | ██████ 1,200   | █████████ 1,800    | ███ 500      |
| Davao Oriental  | ███ 500        | ████ 800           | ██████ 1,200 |

### 3. Human Analytical Narrative (The 'Why' Factor)
The data chart clearly shows an abrupt 18% decline in smallholder cacao output centered in late 2023, dropping from 2,200 MT in 2022 to 1,150 MT in 2023. While the automated AI analysis summary attributed this drop solely to 'weather variability,' the human context reveals a more complex story.

This drop emphasizes the urgent need for NEDA and local LGUs to invest heavily in smart solar-powered irrigation infrastructure—but not uniformly across all provinces. The 18% decline was concentrated in Davao Oriental's coastal farms, which were disproportionately affected by Super Typhoon Odette's aftershocks. Meanwhile, Davao del Norte's protected lowland farms saw a 15% increase in yield during the same period, suggesting that geographic vulnerability and farm management practices are just as critical as weather patterns.
