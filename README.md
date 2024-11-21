# MS in Data Science

## Module: ITC 6001 – Introduction to Big Data

### Term: Fall 2024  
**Assessment:** Project  
**Weight:** 50%  
**Duration:**  

**Deliverables:**
- Report in TurnitIn  
- Code in Blackboard  
- Code in GitHub  
- Oral examination/presentation of your work  

**Method of Submission:** TurnitIn and Blackboard  
**Deadline:** Last Week of the course  

---

## General Instructions

Your project involves conducting a series of experiments, analyzing the observations, and drawing conclusions. Data will either be provided or collected, and Python is recommended (if using a different language, inform the instructor). Use relevant libraries to process the data and include tables, diagrams, and visualizations to present your findings.

### Deliverables:
1. **Code** in Blackboard (Python), including instructions for execution.
2. **Report** (3000±500 words) to be submitted on TurnitIn. The report must document all experiments and conclusions. If exceeding the word limit, use an appendix.
3. **Oral Presentation**.
4. **Code** in GitHub.

**Team Size:** 3 members  

---

### Grading and Peer Marking:

#### Example:
| Person Being Rated | Person-1 | Person-2 | Person-3 |  
|---------------------|----------|----------|----------|  
| **Person Doing the Rating** | 1.25 | 1 | 0.75 |  
| Person-2 | 1.10 | 1.10 | 0.80 |  
| Person-3 | 1 | 1 | 1 |  

| **Average Rate** | 1.12 | 1.03 | 0.85 |  
| **Individual Score** (80% Project Grade) | 89.6 | 82.4 | 68 |

**Explanation:**  
Teams consist of three members, and each member rates the contribution of themselves and others. The ratings must sum to the team size. A rating of `1.00` means expected contribution; less than `1.00` means less contribution; more than `1.00` means greater contribution.

---

### Coding:
- Use Python and libraries such as JSON, CSV, Pandas, NumPy, visualization tools, and databases as needed.  
- No other frameworks are permitted.

---

## Project Questions:

### Q1: Understanding the Data - Exploration (15%)
- **Dataset:** Obtain the MovieLens 100k dataset.  
- **Tasks:**  
  - Plot the number of movies seen by each user and the frequency of each rating.  
  - Detect outliers (e.g., using Z-score with a threshold like 3).  
  - Convert the ratings data into a matrix format for later use.  

**Example: Original Format**  
| user | item | rating |  
|------|------|--------|  
| u1   | i1   | 2.3    |  
| u2   | i2   | 5.3    |  
| u1   | i4   | 1      |  

**Transformed Format**  
| user | item1 | item2 | item3 | ... |  
|------|-------|-------|-------|-----|  
| u1   | 2.3   | 1.7   | NaN   | ... |  
| u2   | NaN   | 5.3   | 1     | ... |  

---

### Q2: Basic Recommender System (20%)
- **Objective:** Build a basic recommender system.  
- **Steps:**  
  - Randomly split user interaction data (80% training, 20% testing).  
  - Two versions:  
    1. Recommend top-rated movies.  
    2. Recommend random movies.  
  - Evaluate results using MAE, RMSE, precision, recall, and F1.

---

### Q3: Collaborative Filtering Recommender System (20%)
- **Objective:** Build a collaborative recommender system.  
- **Steps:**  
  - Use cosine similarity for user-based similarity.  
  - Generate the top 5 recommendations per user.  
  - Hide 20% of the interaction matrix randomly and evaluate predictions using MAE, RMSE, precision, recall, and F1.

---

### Q4: Improvements (20%)
- **Tasks:**  
  - Tune model hyperparameters (e.g., number of neighbors).  
  - Experiment with thresholds (e.g., users with more than 20 ratings).  
  - Incorporate additional features (e.g., movie genres, timestamps, demographic data).

---

### Q5: Presentation (10%)
- **Deadline:** Last day of the course.  
- **Content:** Summarize the dataset, preprocessing steps, methodology, results, and conclusions.  
- **Requirement:** All team members must participate.

---

### Q6: Report Quality (15%)
- The report must be self-contained and well-organized into meaningful sections. Use tables and diagrams for better readability.

---

**Academic Ethics:** All work must be original and done without unauthorized assistance.

