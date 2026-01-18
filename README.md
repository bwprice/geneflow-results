# GeneFlow eDNA Biodiversity Survey Results

Interactive reports from the GeneFlow environmental DNA (eDNA) biodiversity survey of chalk streams.

## 🌐 View Online

Visit the live site: **[https://your-username.github.io/geneflow-results/](https://your-username.github.io/geneflow-results/)**

## 📊 What's Included

- **Master Report** - Comprehensive analysis of all rivers and sites
- **10 River Reports** - Detailed findings for each surveyed river
- **82 Site Reports** - Individual report cards for each sampling location

## 🏞️ Rivers Surveyed

- Ash
- Beane
- Chess
- Ewelme Brook
- Hamble Brook
- Mimram
- Misbourne
- Rib
- Stevenage Brook
- Upper Lea

## 📁 Repository Structure

```
geneflow-results/
├── index.html                    # Landing page with navigation
├── geneflow_edna_report.html     # Master report
├── rivers/
│   └── river_report_*.html       # Individual river reports
├── sites/
│   └── site_report_*.html        # Individual site reports
├── .nojekyll                     # Disables Jekyll processing
└── README.md                     # This file
```

## 🔧 Enabling GitHub Pages

1. Go to repository **Settings**
2. Navigate to **Pages** (in the left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait a few minutes for deployment

Your site will be available at `https://your-username.github.io/geneflow-results/`

## 📝 Updating Reports

Reports are generated from the main GeneFlow analysis pipeline. To update:

```bash
cd C:\GitHub\GeneFlow\scripts
python deploy_reports.py
cd C:\GitHub\geneflow-results
git add .
git commit -m "Update reports"
git push
```

## 🧬 About GeneFlow

GeneFlow uses environmental DNA (eDNA) metabarcoding to assess freshwater invertebrate biodiversity in chalk streams. This non-invasive technique detects species from DNA shed into the water, providing a comprehensive snapshot of aquatic communities.

---

*Natural History Museum London*
