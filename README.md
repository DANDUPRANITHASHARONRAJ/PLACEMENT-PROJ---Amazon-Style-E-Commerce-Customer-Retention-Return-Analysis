# PLACEMENT-PROJ---Amazon-Style-E-Commerce-Customer-Retention-Return-Analysis


ecommerce-retention-analysis/
  ├── data/               # raw CSV datasets
  ├── sql/                # schema + queries
  ├── notebooks/          # Python EDA + ML
  ├── powerbi/            # dashboards
  ├── docs/               # reports, screenshots
  └── README.md
# Create project folder
mkdir ecommerce-retention-analysis
cd ecommerce-retention-analysis

# Create subfolders
mkdir data sql notebooks powerbi docs

# Create README
touch README.md

# Initialize Git
git init

# Create first commit
git add .
git commit -m "Initial project structure"

# Create GitHub repo (requires GitHub CLI)
gh repo create ecommerce-retention-analysis --public --source=. --remote=origin --push
