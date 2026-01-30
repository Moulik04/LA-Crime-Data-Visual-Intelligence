# Visual Intelligence Dashboard: Los Angeles Crime Analysis (2010-Present)

### 1. Project Overview
Solved the problem of information asymmetry for new Los Angeles residents by transforming raw, complex crime data into an interactive visual narrative to support data-driven decisions on housing, commuting, and personal safety.

### 2. Dataset
Utilized the **Los Angeles Crime Dataset**, containing over a decade of criminal activity records. Key attributes analyzed include:
* **Temporal:** `TIME OCC` (Time of occurrence) and `DATE OCC`.
* **Geographical:** `AREA NAME` and `Latitude/Longitude` coordinates.
* **Demographic:** `Vict Age` (Victim Age) and `Vict Sex`.
* **Incident Details:** `Crime Code Description` and `Weapon Description`.

### 3. Approach
* **User-Centered Design:** Conducted a deep **Audience Analysis** to define specific personas (new residents) and their unique safety concerns.
* **Task Abstraction:** Identified seven core analytical tasks, including identifying hotspots, temporal patterns, and age-based vulnerability.
* **Iterative Prototyping:** Developed the dashboard through three phases: 
  1. **Storyboarding:** Manual sketches of visualization idioms.
  2. **Development:** Building interactive worksheets in Tableau.
  3. **Validation & Refinement:** Implementing feedback to add "Holiday Trend" analysis and specific weapon-type filters.
* **Tools:** Tableau Public, Figma/Storyboarding tools, and OpenStreetMap.

### 4. Results
* **Metrics:** Identified **77th Street** and **Central** as the highest frequency areas (15,000+ incidents). 
* **Insights:** Discovered a distinct "Noon Spike"—crime peaks at 12:00 PM and hits its lowest point at 5:00 AM.
* **Interactivity:** Successfully implemented cross-chart filtering, allowing users to click a "Hotspot" on a map and instantly see the average victim age and hourly crime distribution for that specific neighborhood.



### 5. Key Learnings
This project mastered the **"Full-Stack Data Storytelling"** workflow. I learned that the best visualization isn't the most complex one, but the one that answers a user's question fastest. I gained experience in **Domain-Level Validation**, ensuring that my technical choices (like using a time-series line chart for holiday deviations) aligned perfectly with the end-user's goal of avoiding high-risk periods. It taught me how to bridge the gap between backend data processing and frontend UX design.
