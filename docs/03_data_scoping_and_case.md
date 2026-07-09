# Document 03: Data Scoping & Case Development

## 📊 1. Sourcing Data & Partnerships
To challenge teams with realistic front-office scenarios, the Analytics & Case Development committee secures a combination of open-source and proprietary dataset pipelines.

### Data Assets Under Consideration
1. **NBA API (Open Source):** Standard box scores, shooting splits, play-by-play data, lineup configurations, and tracking summaries (e.g., speed, distance, touch time).
2. **Sportradar (Partnership):** Real-time play-by-play feeds and advanced team statistics.
3. **Player Tracking Data (Proprietary Sample):** Anonymized spatial coordinate tracking data (e.g., 25 frames per second player/ball coordinates) for a subset of games, sourced via corporate analytics partnerships.
4. **Draft and Combine Historical Data:** Anthropometric measurements, athletic testing, and NCAA/international historical statistics.

---

## 🔒 2. Data Cleaning & Internal Asset Lock
* **Target Lock Date:** **October 1, 2026**
* **Goal:** The Analytics team must compile, clean, and verify all datasets. The final data package will be locked, zipped, and placed in a secure, access-restricted server.
* **Confidentiality:** To prevent leaks, data schemas, sample rows, and case prompts are strictly confidential. Only the Analytics Pillar chair and the direct faculty advisors will have read access prior to the launch.

---

## 💡 3. Potential Case Prompt Themes
The committee will choose one of the following high-impact themes for the 2026–2027 competition prompt:

### Option A: Spatial Defensive Efficiency & Player Tracking
* **Objective:** Use spatial player tracking data to evaluate off-ball defensive impact.
* **Focus:** How do defensive players adjust their positioning relative to ball movement, and how does this affect opponent shot quality? Teams must construct a metric that quantifies "defensive gravity" or "space protection."

### Option B: Lineup Optimization Under Salary & Workload Constraints
* **Objective:** Build a dynamic rotation engine for an NBA head coach.
* **Focus:** Given historical lineup synergy, injury risks, player fatigue levels, and salary cap limits, construct an optimization model that outputs game-by-game player rotations.

### Option C: The Draft Scout - Projecting Synergy & Role Fit
* **Objective:** Evaluate incoming college players against existing NBA team rosters.
* **Focus:** Identify which draft prospects provide the highest incremental value to specific lottery teams, factoring in shooting chemistry, defensive versatility, and usage rates.

---

## 🚀 4. Data Distribution & Support
* **Release Date:** **December 11, 2026**
* **Method:** Pushed to the official competition GitHub repository as raw CSVs / parquet files, with access links emailed to registered teams.
* **Technical Support:** The committee will host a virtual "Tip-Off Webinar" on launch day to walk through the data schemas and host a Q&A session. No further data-related queries will be answered individually after this session.

---

## 📝 5. Benchmark Case Study: Star Player Effectiveness

As a baseline reference for case scoping, the Executive Committee uses a structured two-part analytics task focused on player movement and teammate synergy.

### Task Concept: "When are Star Basketball Players Most Effective?"
This model task leverages historical play-by-play (NBA) data to investigate how roster fluidity and high-profile team acquisitions impact individual play-styles and overall team outputs.

#### Part A: Teammate Synergy & Adaptation (Individual Player Focus)
* **Question:** How does the play of a star basketball player change depending on the teammates they are playing with?
* **Details:** Teams analyze a high-profile player who recently moved to a new roster, or the team they joined, to observe how other star players adjust to their presence.
* **Examples to Model:** 
  * Kevin Durant joining Stephen Curry (Golden State Warriors).
  * Damian Lillard joining Giannis Antetokounmpo (Milwaukee Bucks).
  * Kyrie Irving and Klay Thompson joining Luka Dončić (Dallas Mavericks).
* **Key Performance Metrics:**
  * **Shot Selection & Mechanics:** Changes in shot types (e.g., catch-and-shoot vs. pull-ups, distance, defender distance).
  * **Efficiency:** TS% (True Shooting Percentage) and eFG% (Effective Field Goal Percentage) variations based on on-court lineups.
  * **Playmaking:** Direct pass distributions, assist-to-turnover ratios, and off-ball movement spacing indicators.
  * **Workload Management:** Rest patterns, minutes played, and defensive workload offset.

#### Part B: Aggregate Team Performance (Team-Level Focus)
* **Question:** What is the impact of adding a "star" player to the performance of a team?
* **Details:** Teams must select a focal franchise (or aggregate multiple trade cohorts) and quantify if the addition of a star player results in a measurable, statistically significant boost in overall team efficiency.
* **Key Performance Metrics:**
  * **Plus/Minus (+/-):** Traditional, On/Off splits, and adjusted plus-minus modeling.
  * **Offensive & Defensive Ratings:** Points scored and allowed per 100 possessions.
  * **Teammate Redistribution:** Quantifying if the star addition elevates teammate output (synergy) or suppresses their usage (cannibalization).

### Deliverable Guidelines
Teams submit 2 to 3 polished summary slides for each task. The slides must focus on clear visualizations, charts, and strategic conclusions (no raw programming code in the presentation body; implementation scripts and regression parameters are relegated to the GitHub repository appendix).

### Case Rubric Breakdown
* **Question Validation (10%):** Selection and justification of a logically sound research question.
* **Empirical Approach (40%):** Suitability and mathematical validity of the metrics, models, and data frames selected.
* **Strategic Insights (40%):** Development of meaningful, basketball-informed conclusions applicable to front-office decision-makers.
* **Style & Presentation (10%):** Clarity, visual appeal, and ease of explanation.
