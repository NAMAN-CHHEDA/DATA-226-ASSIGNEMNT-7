# 📊 DATA 226 - Assignment 7 (dbt + Snowflake)

### Author: Naman Chheda  
### Course: DATA 226 - ELT Deep Dive (Week 10)

---

## 🎯 Objective
This assignment demonstrates the complete setup of a **dbt project** using the **Snowflake connector**, following the Week 10 class instructions.  
It includes input and output models, snapshots, and testing — all connected to Snowflake.

---

## 🧱 Project Structure
bash```
dbt/
├── dbt_project.yml
├── models/
│ ├── input/
│ │ ├── user_session_channel.sql
│ │ └── session_timestamp.sql
│ ├── output/
│ │ └── session_summary.sql
│ ├── schema.yml
│ └── sources.yml
├── snapshots/
│ └── snapshot_session_summary.sql
├── .gitignore
└── README.md
```
