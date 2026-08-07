[README (1).md](https://github.com/user-attachments/files/30812374/README.1.md)
# SENTINEL — Cyber Threat Intelligence Platform
### Milestone 1 | Defense Industry CTI Platform

---

## Overview
SENTINEL is a Streamlit-based CTI platform focused on the U.S. Defense Industrial Base (DIB).
It covers industry background, stakeholder personas, threat trends, critical assets, Diamond Models,
an interactive dashboard, and an intelligence buy-in business case.

---

## Setup & Run Instructions

### 1. Requirements
- Python 3.9 or higher
- pip

### 2. Install Dependencies
```bash
pip install streamlit pandas plotly
```

### 3. Run the App
```bash
streamlit run cti_platform_app.py
```

The app will open automatically in your browser at `http://localhost:8501`.

---

## File Structure
```
cti_platform_app.py    ← Main Streamlit application (single file)
README.md              ← This file
```

No external data files are required. All data is embedded in the app.

---

## Navigation
Use the **sidebar** to navigate between sections:
-  Overview
-  Industry Background
-  Stakeholders & User Stories
-  CTI Use Case
-  Threat Trends (tabbed: Global, Exploits, Industry Targets, Threat Actors)
-  Critical Assets (with risk matrix)
-  Diamond Models (APT40, Lazarus Group)
-  Interactive Dashboard (filters, charts, KPIs, threat table)
-  Intelligence Buy-In
-  About & Team

---

## Customization Before Submission
1. **Team section** — Replace `[ STUDENT NAME 1 ]` through `[ STUDENT NAME 4 ]` in the About & Team page
   with your actual names, roles, and contribution descriptions.
2. **Electronic Signatures** — The app auto-fills today's date. Names are the signature.

---

## Milestone 1 Checklist (What's New)
All items listed in the in-app changelog at the top of every page:
- ✓ Initial Streamlit app scaffolding and professional UI theme
- ✓ Industry Background (Defense sector)
- ✓ Stakeholder personas and user stories
- ✓ CTI Use Case / Threat-Model-Backed Design
- ✓ Threat Trends (global + defense-specific, tabbed)
- ✓ Critical Asset Identification (7 assets)
- ✓ Two Diamond Models (APT40, Lazarus Group)
- ✓ Interactive Dashboard (filters, bar chart, pie chart, impact chart, table, 4 KPIs)
- ✓ Intelligence Buy-In (data-supported business case with chart)
- ✓ About & Team with electronic signatures
