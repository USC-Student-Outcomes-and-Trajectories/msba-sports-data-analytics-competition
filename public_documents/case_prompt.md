# MSBA Sports Data Analytics Competition: Official Case Prompt
## In-Game Strategy & Real-Time Decision-Making for Coaches and Basketball Executives

---

## 🏀 1. Philosophy & Executive Overview

This competition prompt is deliberately **open-ended**. In the high-stakes environment of professional basketball analytics, success is rarely about finding a single "correct" formula or benchmark. Instead, it demands a **thoughtful, rigorous solution** that deeply analyzes operational realities, addresses genuine in-game constraints, and establishes a meaningful, strategically relevant decision framework.

In this spirit, the primary deliverable is **not** a traditional slide deck, static PDF report, or academic paper. Modern coaches and front-office executives operate under intense time pressure; they cannot parse dense tables or navigate multi-page slide decks during live game action. 

Instead, teams are challenged to design and deploy a **single live dashboard or interactive visualization** that an end-user can intuitively understand at a glance, providing immediate, actionable insights to guide live coaching and in-game tactical decisions.

---

## 🎯 2. The Official Prompt

> **Create an analytics solution (live dashboard or graphic) that can help coaches or basketball executives make actionable decisions during a game.**

Your solution must empower coaches, assistant coaches, and front-office analysts on the bench to make high-impact tactical interventions as game situations unfold.

### Illustrative Strategic Questions
Teams have complete freedom to choose their focal strategic problem. Example problems teams could solve include, but are not limited to:

1. **Player Decision Quality in Real Time:**  
   *How well are players making decisions at any given point in a game? Based on empirical data, what constitutes a high-quality versus a low-quality decision in that context?*
2. **Dynamic Substitution & Fatigue Optimization:**  
   *How "well" are the players currently on the court playing, and what is the optimal moment to substitute them out before their efficiency, defensive intensity, or shooting performance experiences a sharp decline?*
3. **Foul Risk & Lineup Vulnerability:**  
   *How at-risk are active players of committing a foul given the current in-game situation (e.g., matchup, pace, referee tendencies, court location, quarter/time remaining), and how should that dictate substitution and rotation adjustments?*

*Teams may explore any other impactful in-game decision problem, provided it directly translates data into coachable, real-time action.*

---

## 🚀 3. Deliverables & Specifications

Submissions must consist of two core components: a **Live Interactive Application** and a **Reproducible GitHub Repository**.

### Deliverable A: Live Interactive Dashboard / Visual Tool
* **Live & Interactive:** Must be hosted online and fully functional (e.g., Streamlit, Dash, Shiny, Vercel, Observable, Tableau Public, or custom web application) so that judges can actively interact with and stress-test the tool in real time.
* **Intuitively Self-Explanatory:** The visualization must be understandable at a glance. Coaches and executives have seconds—not minutes—to interpret information. The design should minimize cognitive load and eliminate ambiguous jargon.
* **Dynamic Scenario Filtering:** The tool must give judges the ability to pick a particular game, time, or in-game situation to dynamically contextualize and set the relevance of the underlying data.
* **Single Dashboard / Visualization:** The interface should function as a unified, cohesive command center or single-view visual solution rather than a disparate collection of unrelated charts.

### Deliverable B: Public GitHub Repository & Technical Documentation
* **Source Code:** Clean, well-structured, and documented code (Python, R, JavaScript, etc.) demonstrating how the data was ingested, transformed, modeled, and visualized.
* **Detailed README.md Documentation:**
  * Direct URL link to the live demo application.
  * Clear explanation of the business and coaching problem addressed.
  * Mathematical, statistical, or machine learning methodology and data definitions.
  * Local reproduction instructions and dependency configuration (`requirements.txt`, `environment.yml`, or `package.json`).
  * Explicit disclosure of any AI assistance tools utilized and how they supported the project.

---

## 📊 4. Data Scope & Integrity

* **Exclusivity of Provided Data:** Teams **must only use the data provided** for this competition. External scraping or blending with unauthorized third-party datasets is strictly disallowed to ensure fair, equal-footing evaluation across all participating institutions.
* **Scope:** Teams are free to filter, aggregate, engineer features, and model subsets of the provided data (e.g., specific teams, quarters, player pairings, or game contexts) to maximize the precision and relevance of their live tool.

---

## ⚖️ 5. Evaluation Rubric

Judges (comprising faculty and NBA analytics leaders) will evaluate submissions based on four core criteria:

| Evaluation Dimension | Weight | Description |
| :--- | :---: | :--- |
| **Clarity of Visual** | **30%** | **Ease of interpretability and understanding.** Can an executive or coach understand the core takeaway within seconds? Is the design clean, intuitive, and visually disciplined? |
| **Actionability** | **35%** | **Direct translation into an immediate decision.** Does the tool recommend or clearly enable a specific tactical adjustment (e.g., call a timeout, initiate a substitution, shift defensive coverage, alter shot selection)? |
| **Feasibility** | **20%** | **Real-world operational viability.** Can this decision reasonably and realistically be executed in the heat of a live game situation under NBA rules and pacing? |
| **Technical Rigor & Defense** | **15%** | **Code quality, documentation, and conceptual defense.** How well-engineered is the codebase? Can the team articulate, justify, and defend their analytical framework and assumptions? |

---

## 🤖 6. Artificial Intelligence (AI) Policy

* **Allowed and Encouraged:** Teams are explicitly permitted and encouraged to leverage modern AI tools (including LLMs, code generation assistants, and design tools) to build, refine, and accelerate their solutions.
* **Evaluation on Execution & Defense:** Teams will be evaluated strictly on the **quality of the tool created**, the **clarity and usability of the interface**, and their **ability to explain, justify, and defend** their design choices and analytical logic during Q&A with the judges. AI cannot replace sound strategic thinking and statistical reasoning.
