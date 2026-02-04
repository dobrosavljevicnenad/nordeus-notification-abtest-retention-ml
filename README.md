# Push Notification Timing Optimization  
### A/B Test Analysis, Retention Impact & Predictive Modeling

This project analyzes a randomized A/B experiment evaluating the optimal timing of push notification permission prompts in a mobile game.  
The goal is to maximize opt-in rate while ensuring minimal negative impact on player retention.

Beyond causal A/B testing, the project explores early behavioral signals and builds predictive models for opt-in and retention.

---

## Key Questions

- Does showing the push permission popup immediately outperform showing it after the tutorial?
- What is the impact on short-term and long-term retention?
- Can early engagement predict opt-in and retention?
- How to avoid common pitfalls such as selection bias and data leakage?

---

## Main Findings

- Early popup increases opt-in rate by ~23 percentage points (highly significant)
- Small negative impact on Day 1 retention, no significant impact on Day 7 and Day 14
- Early engagement strongly predicts both opt-in and retention (AUC ≈ 0.71 and ≈ 0.96)
- Naively using post-exposure telemetry introduces data leakage and overestimates model performance

---

## Author

Nenad Dobrosavljevic  
Nordeus - Junior Data Science Task
