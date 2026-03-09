
#  South Africa's Informal Economy: Contribution to Economic Growth & the Labour Market

> A quantitative research project conducted at **Statistics South Africa (Stats SA)**  
> Cape Peninsula University of Technology — Mathematical Sciences Project 3 (MSP360S)  
> Author: **Mkhonto Hendry Mike** | Student No: 221026908  
> Supervisor: Dr G. Buzuzi | Company Mentor: Zukile Ncapayi | July 2024

---

##  Project Overview

This project investigates the **nature, extent, and contribution of South Africa's informal economy** to economic growth and the labour market, with a focus on the **Western Cape Province (City of Cape Town)** in 2023.

Using data from Statistics South Africa's **Quarterly Labour Force Survey (QLFS) Q4 2023**, the study applies **binary logistic regression** to examine how demographic factors — including gender, age, education, geography, and province — influence participation in the informal economy.

---

##  Research Questions

1. What is the current state and structure of the informal economy in South Africa?
2. What are the primary challenges informal businesses face?
3. What economic advantages come from formalizing the informal economy (GDP, employment, tax revenue)?
4. How can government, civil society, and business collaborate on formalization strategies?

---

##  Repository Structure

```
├── data/
│   └── QLFS_Q4_2023/          # Stats SA Quarterly Labour Force Survey dataset
├── scripts/
│   └── analysis.R             # R script for logistic regression & visualizations
├── figures/
│   ├── fig1_population_group.png
│   ├── fig2_gender_education.png
│   ├── fig3_province_employment.png
│   ├── fig4_gender_sector.png
│   ├── fig5_metro_sector.png
│   └── fig6_age_sector.png
├── report/
│   └── MSP360S_Final_Report.pdf
└── README.md
```

---

##  Tools & Technologies

| Tool | Purpose |
|------|---------|
| **R** | Statistical analysis & modelling |
| **Binary Logistic Regression** | Predicting informal economy contribution |
| **Stats SA QLFS Q4 2023** | Primary dataset (~30,000 households) |
| **ggplot2** | Data visualizations |

---

##  Methodology

- **Data Source:** Stats SA Quarterly Labour Force Survey (QLFS), Q4 2023
- **Sample Size:** 16,649 employed participants (formal + informal)
- **Model:** Binary Logistic Regression
- **Software:** R
- **Significance Level:** p < 0.05

### Model

```
Logit(P) = β₀ + β₁(Informal Employment) + β₂(Gender) + β₃(Age Group)
                + β₄(Education Status) + β₅(Geography Type) + β₆(Province)
```

Where **P** = probability that the informal economy contributes to economic growth and the labour market.

---

##  Key Findings

| Finding | Detail |
|--------|--------|
| **Informal sector share** | 31.12% of employed participants (5,181 of 16,649) |
| **Dominant population group** | African/Black — 70.7% of informal employment |
| **Gender gap** | Males dominate both formal and informal sectors |
| **Education link** | Lower education → higher probability of informal employment |
| **Urban concentration** | 3.3M of 5M informal workers are in urban areas |
| **Top provinces** | Gauteng, KwaZulu-Natal, and Western Cape lead informal activity |

---

##  Visualizations

| Figure | Description |
|--------|-------------|
| Fig 1.1 | Distribution of Informal Employment by Population Group |
| Fig 1.2 | Employment Status by Gender and Education Level |
| Fig 1.3 | Province vs Employment Status |
| Fig 1.4 | Employment by Gender and Sector |
| Fig 1.5 | Metro Code by Province and Sector |
| Fig 1.6 | Age Group Distribution by Sector |

---

##  Recommendations

-  **Financial access** — Government loans and microfinancing for informal entrepreneurs
-  **Skills development** — SETA training programs for informal workers
-  **Public-Private Partnerships** — Formal-informal sector integration
-  **Digital tools** — Mobile platforms for training and financial services (modelled on India's approach)
-  **Infrastructure** — Improved urban and rural infrastructure for informal traders
-  **Social protection** — UIF and social security coverage for informal workers

---

##  Acknowledgements

This research was conducted in partnership with **Statistics South Africa (Stats SA)**. Special thanks to **Zukile Ncapayi** (company mentor) and **Mr Sive** for providing access to the QLFS dataset, and to **Dr G. Buzuzi** for academic supervision throughout the project.

---

##  Key References

- Hart, K. (1973). Informal income opportunities and urban employment in Ghana.
- Rogan, M. & Skinner, C. (2017). The nature of the South African informal sector.
- Statistics South Africa (2020). Quarterly Labour Force Survey.
- Vanek, J. et al. (2014). Statistics on the informal economy — WIEGO Working Paper.

---

##  License

This project is for academic purposes. Data sourced from Statistics South Africa is subject to Stats SA's data usage terms.

---

*Cape Peninsula University of Technology — Diploma in Mathematical Sciences, 2024*
