# Contributing Guidelines

First of all, thank you for monitoring the iOS audio ecosystem with us. This project is a strictly non-commercial, independent scientific study. We welcome contributions from developers, data scientists, and audio engineers who want to expose algorithmic gatekeeping and platform de-professionalization.

By contributing to this repository, you agree that your contributions will be licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

---

## Critical Rules for Contributions

To protect the integrity of this forensic study and prevent sabotage from commercial entities or shadow-governance actors, all contributions must strictly adhere to the following rules:

1. **No Commercial Interference:** Contributions driven by commercial interests, corporate App Store Optimization (ASO) agencies, or representatives of centralized audio forums under investigation will be immediately rejected.
2. **Data Integrity First:** Since our dataset relies on uncorrupted daily iTunes API snapshots, any submission that modifies existing SQLite schemas or introduces unverified data points must be fully documented.
3. **Price Analysis Restriction:** As stated in our core methodology, we explicitly do **NOT** track or analyze price histories. Do not submit pull requests, scripts, or database columns related to dynamic price tracking.

---

## How You Can Contribute

### 1. Enhancing AI & Statistical Analysis (`/analysis`)
We are actively looking for improvements in our Jupyter Notebooks and Python scripts regarding:
- **Natural Language Processing (NLP):** Refining our Topic Modeling (BERTopic) and Semantic Shift Analysis on the `description` column.
- **Anomaly Detection:** Tweaking Scikit-Learn algorithms (e.g., Isolation Forests) to better isolate stable Pro-Apps from low-effort SEO spam.
- **Data Visualization:** Creating clean, scannable charts using Matplotlib or Seaborn that plot the divergence of terms like "VST" vs. "Digital Signal Processing".

### 2. Forensic Database Maintenance (`/data`)
If you find bugs in our SQLite retrieval scripts or want to optimize the database performance:
- Help optimize index queries for the SQLite database to speed up long-term daily tracking.
- Propose robust methods for tracking "Ghost/Purged Apps" (detecting when an app entry permanently disappears from the daily API cycle).

### 3. Case Studies & Documentation (`/studies`)
If you have verifiable, empirical evidence of API misindexing or targeted forum censorship:
- Submit structured markdown case studies backed by raw API server logs or platform traffic screenshots.

---

## The Pull Request (PR) Process

1. **Fork the Repository:** Create your own branch from `main`.
2. **Clean Code & No Pseudocode:** Ensure all Python scripts are fully functional, production-ready, and contain zero pseudocode or forbidden inline placeholders.
3. **Verify against the SQLite Schema:** If your scripts interact with the database, test them locally against the current version of the `.sqlite` file.
4. **Open a PR:** Describe your changes clearly. State exactly how your patch improves the analytical or forensic capabilities of the study.

---

## Code of Conduct & Academic Integrity

This is a space for objective, metric-driven research. We do not engage in personal attacks or emotional arguments. Every claim made in this repository must be backed by reproducible data extracted from the iTunes API or verified platform logs. 

Thank you for helping us maintain an uncorrupted, scientific record of the mobile audio market!
