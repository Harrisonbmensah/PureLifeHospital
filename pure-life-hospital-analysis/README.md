# Pure Life Hospital: Business Analysis of Patient Records

A health-intelligence analysis of Pure Life Hospital's patient and operational records, built in **Power BI** and presented as a PowerPoint deck. This repository also publishes the findings as a web page (`index.html`).

**Author:** Harrison Baffoe-Mensah

## Key figures

| Metric | Value |
|---|---|
| Revenue | $294.03M |
| Admissions | 5,000 |
| Average length of stay (ALOS) | 3.56 days |
| Mortality rate | 2.22% |
| Discharged | about 85% |

## Findings

1. **Outpatient services drive activity:** 2.5K outpatient, 1.5K inpatient and 1.0K emergency admissions (outpatient is about 50%).
2. **Revenue is seasonal:** dips around months 2, 4 and 7; peaks around months 6 and 11.
3. **Digestive system disorders lead diagnoses (873)**, ahead of infectious and parasitic diseases (692), cardiovascular diseases (554) and malignant neoplasms (546).
4. **Mortality (2.22%)** needs department-level investigation.
5. **ALOS (3.56 days)** looks efficient, but readmissions should be checked.
6. **Discharge performance is strong** (about 85% discharged).

Each finding comes with a business interpretation and recommendations on the web page and in the deck.

## Repository structure

```
pure-life-hospital-analysis/
├── index.html                  # web version of the analysis (self-contained)
├── README.md
├── .gitignore
├── assets/
│   └── logo.png                # Pure Life Hospital logo
├── presentation/
│   ├── Pure_Life_Hospital_Presentation.pptx
│   └── Pure_Life_Hospital_Presentation.pdf
└── powerbi/
    └── (add Power_Bi_Project_Final.pbix here)
```

## Tools

Power BI (data model and dashboards), PowerPoint (presentation), HTML/CSS (web page).

## Publish with GitHub Pages

1. Create a new repository on GitHub and upload the contents of this folder.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your page will be live at `https://<your-username>.github.io/<repository-name>/`.
