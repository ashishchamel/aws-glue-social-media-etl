# 📊 Social Media Data Integration & Analysis using AWS Glue  

A complete ETL pipeline built on AWS Glue that integrates and analyzes social media data from Twitter and Blogs.

---

### 🧠 What This Project Does
This project extracts CSV data from Amazon S3 buckets, transforms it using AWS Glue Visual ETL (joins, regex extraction, aggregation), and loads the cleaned results back into an S3 output bucket.  
All steps are shown with screenshots and explanations in the attached report.

---

### 🗂️ Folder Overview

```
aws-glue-social-media-etl/
├── README.md
├── data/
│   ├── raw/ → raw Twitter & Blog data
│   └── processed/ → sample output
├── docs/
│   ├── images/ → optional screenshots
│   └── report/ → project documentation (PDF + guidelines)
└── src/ → placeholder for AWS Glue scripts
```

---

### 📄 What’s Inside

| Folder | Description |
|--------|--------------|
| `docs/report/` | Contains project reports and Simplilearn guideline |
| `data/raw/` | Raw datasets (`tweets_raw.csv`, `blogs_raw.csv`) |
| `data/processed/` | Contains sample ETL output |
| `src/` | Placeholder describing AWS Glue job setup |

---

### 🧾 Implementation Summary
The ETL job was built entirely in **AWS Glue Studio (Visual ETL)**.  
Since AWS Glue stores scripts internally in your AWS account, no `.py` files are downloadable.  
All transformations (joins, drop fields, regex extraction, aggregation) and results are fully documented in the PDF report (`docs/report/ETL_Project_Report.pdf`).

---

### 🧩 Sample Output (from included CSV)

| User ID | Blog ID | Tweet Count | Min Timestamp |
|----------|----------|-------------|----------------|
| 123 | 1 | 5 | 2024-05-20T08:00:00 |

---

### 🧠 Ethical Statement
All datasets included here are sample, anonymized educational data only.  
No real or personal information is used in this project.

---

### 🧑‍💻 Author
**Ashish Chamel**  
