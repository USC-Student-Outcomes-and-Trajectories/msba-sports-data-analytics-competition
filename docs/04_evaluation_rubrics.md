# Document 04: Evaluation Rubrics & Grading Sheets

## 🧑‍🏫 Round 1: Blind Faculty Evaluation (Preliminary Round)
* **Goal:** Evaluate the technical depth, statistical soundness, and reproducibility of the team's submissions.
* **Format:** Blind review. Faculty judges will only see a team's numeric ID, their 15-slide PDF deck, and their GitHub repository.

### Scoring Breakdown (100 Points Total)

```
┌──────────────────────────────────────────────────────────┐
│   Round 1 Score: 100 Points Total                        │
├───────────────┬──────────────────────────────────────────┤
│   40 Points   │   Methodology, Rigor & Reproducibility   │
├───────────────┼──────────────────────────────────────────┤
│   30 Points   │   Basketball Analytics & Insight Depth   │
├───────────────┼──────────────────────────────────────────┤
│   20 Points   │   Executive Communication & Deck Design  │
├───────────────┼──────────────────────────────────────────┤
│   10 Points   │   Actionable Front-Office Strategy      │
└───────────────┴──────────────────────────────────────────┘
```

#### 1. Methodology, Rigor & Reproducibility (40 Points)
* **Code Execution (15 pts):** Does the code run out-of-the-box using the provided environment files? Are there clean, automated scripts to regenerate all models?
* **Statistical Soundness (15 pts):** Are the chosen models appropriate for the data? Are assumptions (e.g., linearity, independent errors) validated? Are proper cross-validation methods used?
* **Data Engineering (10 pts):** Is the data pipeline optimized, cleanly structured, and free of data leakage?

#### 2. Basketball Analytics & Insight Depth (30 Points)
* **Advanced Metrics (15 pts):** Does the team go beyond basic box scores to develop sophisticated, contextual metrics?
* **Contextual Integration (15 pts):** Does the model reflect actual basketball reality (e.g., floor spacing, fatigue, game situation, defensive matchups)?

#### 3. Executive Communication & Slide Deck Design (20 Points)
* **Visual Clarity (10 pts):** Are charts professional, labeled, and easy for an executive to interpret?
* **Narrative Flow (10 pts):** Does the deck present a cohesive story from the problem statement to the final recommendations?

#### 4. Actionable Front-Office Strategy (10 Points)
* **Feasibility:** Are the recommendations realistic for an NBA front-office to implement under the salary cap and collective bargaining agreement (CBA)?

---

## 🏀 Round 2: NBA Finals Judging (Live Final Round)
* **Goal:** Assess the finalists' ability to defend their work under high-stakes questioning by active NBA executives.
* **Judges:** Panel of 3 to 5 NBA analytics professionals.
* **Format:** 15-minute presentation followed by 10 minutes of intense Q&A.

### Scoring Breakdown (50 Points Total)

#### 1. Front-Office Value & translation (20 Points)
* Can this analysis be directly integrated into an NBA scouting report or coaching meeting tomorrow? Does it translate complex math into simple, high-impact basketball concepts?

#### 2. Technical Defense & Q&A Response (15 Points)
* How well do the students defend their mathematical assumptions under scrutiny? Do they demonstrate deep ownership and understanding of their model’s limitations?

#### 3. Presentation Poise & Team Chemistry (15 Points)
* Do all team members present in a polished, professional manner? Is the presentation balanced, or does one person dominate? Are slide transitions smooth?

---

## 🧼 Anonymization Checklist for Operations
To guarantee a 100% blind review in Round 1:
- [ ] Remove university names, logos, or mascots from slide headers, footers, and title pages.
- [ ] Remove student names and email addresses from PDF metadata properties.
- [ ] Scan GitHub repositories for student names, university references, or institutional emails in `README.md`, comments, or commit history.
- [ ] Generate random 3-digit Numeric IDs (e.g., Team 104, Team 207) and rename the PDF files and GitHub repository references accordingly.
- [ ] Maintain a secure master mapping key accessible only to the Operations & Logistics Chair.
