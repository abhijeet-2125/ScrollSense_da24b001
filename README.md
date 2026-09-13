# ScrollSense — Database Design and Implementation

**Author:** Abhijeet Kumar (DA24B001)  
**Programme:** B.Tech in AI & Data Analytics, IIT Madras  
**Database:** SQLite 3.44+

---

## 1. Overview

ScrollSense is a short-video social platform involving users, creators, videos, hashtags, audio tracks, social interactions, moderation, recommendations, and an AI assistant.

This project implements the complete database design and SQLite-based database system for ScrollSense.

The work covers:

- ER-to-relational mapping
- Logical database design
- Functional dependencies and normalization
- BCNF analysis and lossless decomposition
- SQLite schema implementation
- Integrity constraints
- Synthetic data generation
- Analytical SQL queries
- Database views
- Temporal data modelling
- Transaction processing
- Concurrency and isolation demonstrations

The database was designed with emphasis on **data integrity, temporal correctness, auditability, and reproducibility**.

---

## 2. Repository Structure

```text
SCROLLSENSE/
│
├── docs/
│   ├── da24b001_A_B.pdf
│   ├── da24b001_C_D.pdf
│   └── da24b001_E_F_G.pdf
│
├── generate_data.py
├── queries.sql
├── schema.sql
├── scrollsense.db
├── transaction.sql
├── views.sql
└── README.md