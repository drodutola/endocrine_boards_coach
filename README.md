# Endocrine Boards Coach 🩺🤖

An AI-powered study coach and question bank generator for physicians preparing for endocrinology board exams — delivering personalized practice questions, explanations, and performance tracking.

## Overview

Board exam preparation is time-intensive and often relies on static question banks. This tool uses a large language model to generate dynamic, high-yield endocrinology questions tailored to the user's knowledge gaps, with detailed explanations grounded in clinical guidelines.

## Features

- **AI Question Generation:** Dynamically generates board-style MCQs across endocrinology topics (diabetes, thyroid, adrenal, pituitary, reproductive endocrinology, metabolic bone disease, and more)
- **Detailed Explanations:** Each question includes a full explanation with guideline references
- **Performance Tracking:** Tracks correct/incorrect answers by topic to identify weak areas
- **Adaptive Difficulty:** Adjusts question difficulty based on user performance
- **Study Mode vs. Exam Mode:** Timed exam simulation or relaxed review mode

## Tech Stack

- **Language:** Python
- **AI Backend:** OpenAI API / Anthropic Claude API
- **Libraries:** Pandas, JSON, Requests
- **Interface:** Command-line or simple web interface

## How to Run

```bash
git clone https://github.com/drodutola/endocrine_boards_coach
cd endocrine_boards_coach
pip install -r requirements.txt
# Add your API key to .env
python coach.py
```

## Sample Topics Covered

- Type 1 & 2 Diabetes — diagnosis, management, complications
- Thyroid disorders — hypothyroidism, hyperthyroidism, nodules, cancer
- Adrenal disorders — Cushing's, Addison's, pheochromocytoma
- Pituitary disorders — acromegaly, prolactinoma, diabetes insipidus
- Metabolic bone disease — osteoporosis, hyperparathyroidism, Paget's

## Background

Built by a physician with direct clinical experience in endocrinology and a deep interest in AI-assisted medical education. Demonstrates practical LLM application in a high-stakes clinical domain.

## Author

**Dr. Peter Odutola, M.D.** — Physician, AI developer, and medical educator.  
[GitHub Profile](https://github.com/drodutola)
