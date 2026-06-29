# GroupDNA: WhatsApp Chat Analytics

## One-Line Description

A Python-based analytics project that parses exported WhatsApp group chats and generates insights such as activity patterns, participant statistics, response behavior, personality archetypes, and a final analytics report.

---

## Project Overview

GroupDNA analyzes an exported WhatsApp chat and transforms raw conversation data into meaningful statistics and visual summaries using only beginner-level Python concepts.

The project includes:

* Feature 1 – Chat Parser
* Feature 2 – Group Overview
* Feature 3 – Most Active Day and Hour
* Feature 4 – Activity Heatmap (NumPy)
* Feature 5 – Top Words
* Feature 6 – Response Speed & Silent Streaks
* Feature 7 – Personality Archetype Detection
* Feature 8 – Final Analytics Report

---


## Constraints Followed

### Allowed

* Basic Python
* File handling
* Strings
* Lists
* Dictionaries
* Loops
* Functions
* if-else statements
* NumPy (for Activity Heatmap)
* datetime module (for response time calculations)

## Seven-Day Build Log

### Day 1

* Studied the project requirements.
* Built the WhatsApp chat parser.
* Parsed messages, participants, media messages and deleted messages.

### Day 2

* Implemented the Group Overview.
* Calculated participant counts, date range and message statistics.

### Day 3

* Found the busiest day and busiest hour.
* Counted messages by date and hour.

### Day 4

* Built the NumPy Activity Heatmap.
* Generated participant-hour activity matrix.

### Day 5

* Extracted and ranked the most frequently used words.
* Removed punctuation and ignored common stop words.

### Day 6

* Calculated response times.
* Detected silent streaks.
* Implemented personality archetype detection.

### Day 7

* Combined all features into one final analytics report.
* Improved formatting and prepared the project for GitHub submission.

---

## How to Run

1. Clone or download this repository.

2. Make sure Python 3 is installed.

3. Install NumPy if it is not already available:

```bash
pip install numpy
```

4. Place the exported WhatsApp chat dataset (`hostel_bois.txt`) in the project folder.

5. Open `GroupDNA.ipynb` using Jupyter Notebook or Google Colab.

6. Run all notebook cells from top to bottom.

7. The final analytics report will be displayed in the output.

---

## Technologies Used

* Python
* NumPy
* datetime

---

## Dataset

* **hostel_bois.txt** (WhatsApp chat export provided for the project)

---

## Author

Lakshita S
