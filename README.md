# Intelligent Candidate Discovery

**Team:** AIndia

## Overview

This project was developed for the Redrob Data & AI Challenge.

The solution builds an AI-powered candidate ranking engine that processes
100,000 candidate profiles and recommends the most suitable candidates for a
Senior AI Engineer role.

## Approach

The ranking pipeline consists of:

1. Skill Matching
2. Title Relevance Scoring
3. Experience Scoring
4. Final Weighted Ranking

### Final Score

Final Score = 0.50 × Skill Score + 0.30 × Title Score + 0.20 × Experience Score

## Tech Stack

- Python
- Pandas
- JSON
- Google Colab

## Dataset Files Used

- candidates.jsonl
- candidate_schema.json
- job_description.docx
- sample_submission.csv

## Output

A validated CSV file containing the Top 100 ranked candidates.
