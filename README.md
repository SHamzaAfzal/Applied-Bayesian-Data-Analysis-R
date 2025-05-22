# Predictors of Student Performance | Applied Bayesian Data Analysis

Project Goal: Identify key factors influencing student academic performance (GPA/GradeClass) using Bayesian multilevel modeling.

## Key Insights
- Top Predictors:
  - Absences → Strongest negative impact on grades.
  - Study time, tutoring, and parental support → Significant positive effects.
- Models:
  - Ordinal model (GradeClass A-F) outperformed the continuous (GPA) model in interpretability.
  - Hierarchical clustering revealed extracurricular activities as a critical grouping factor.
- Tools: R, brms, Stan, Bayesian inference with weakly informative priors.

## Repository Structure

├── hazzard/                                # code in haphazard manner (before submission)
└── ProjectSubmission.Rmd                   # R scripts for analysis & modeling
└── Group_27.pdf                            # LaTeX report (PDF)
└── Knit_Output_R Code_11March.pdf          # Code output (PDF)
└── ABDA Group# 27.pptx                     # Project Presentation (pptx)
└── README.md                               # Project overview



## Challenges & Learnings
- Addressed divergent transitions in Gaussian models via prior sensitivity analysis.
- Learned the trade-offs between ordinal vs. continuous target variables.

## How to Reproduce
1. Clone repo:
   git clone [repo-url]
2. Run R scripts in scripts/ (see requirements.R for packages).
