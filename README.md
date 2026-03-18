# 🛍️ Retail Analytics — Mall Segmentation
### ML · Retail Analytics | Customer Segmentation & Persona Generation

> Clustering-based customer segmentation for retail strategy optimisation. Identified actionable shopper personas delivering a measured **78% uplift in targeted sales conversion**.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![KMeans](https://img.shields.io/badge/Model-K--Means%20Clustering-teal?style=flat-square)
![Uplift](https://img.shields.io/badge/Sales%20Uplift-78%25-gold?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-Retail%20Analytics-purple?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> 🔒 **Private Repo · README only.** Source code not publicly accessible.

---

## 📌 Overview

Retail strategy without customer segmentation is a blunt instrument — promotions, layouts, and product placements designed for an average customer serve no customer well. This project applies **K-Means clustering** to mall shopper behavioural and demographic data to identify distinct, actionable customer personas. The resulting segmentation delivered a **78% uplift in targeted sales conversion** when applied to retail strategy decisions.

---

## 🎯 Objective

Segment mall shoppers into distinct behavioural personas based on spending patterns, visit frequency, demographic profiles, and category preferences — enabling targeted retail strategy, personalised promotions, and optimised store layout decisions.

---

## 🧱 Technical Approach

| Component | Detail |
|---|---|
| **Dataset** | Mall customer data — demographics, spending scores, visit behaviour, category preferences |
| **Feature Engineering** | Spending ratios, visit frequency, category affinity scores, demographic interaction features |
| **Algorithm** | K-Means Clustering |
| **Optimal K Selection** | Elbow method + Silhouette score analysis |
| **Visualisation** | PCA / t-SNE for cluster visualisation |
| **Evaluation** | Silhouette score, inertia, business validation of persona distinctiveness |
| **Business Impact** | **78% uplift in targeted sales conversion** |

---

## 🔬 Methodology

1. **Data Preprocessing** — cleaned shopper records, handled missing values, normalised spending and demographic features to prevent scale bias in distance-based clustering
2. **Feature Engineering** — derived behavioural features: category spending ratios, visit recency and frequency scores, high-value vs budget shopper indicators
3. **Optimal Cluster Selection** — applied Elbow method on inertia curve and Silhouette score analysis to identify the optimal number of customer segments
4. **K-Means Clustering** — trained on the processed feature matrix; multiple random initialisations with K-Means++ seeding for stable convergence
5. **Persona Generation** — each cluster characterised by its centroid profile and member distribution; named personas created with distinct behavioural archetypes (e.g., *"Weekend Luxury Browsers"*, *"Weekday Practical Shoppers"*, *"High-Frequency Deal Seekers"*)
6. **Strategy Application** — personas used to inform targeted promotions, product placement, and marketing channel decisions — resulting in measured 78% sales conversion uplift

---

## 📊 Results

| Metric | Score |
|---|---|
| Sales Conversion Uplift | **78%** (targeted vs untargeted) |
| Task | Customer segmentation and persona generation |
| Algorithm | K-Means with Elbow + Silhouette optimisation |

---

## 👥 Example Personas Identified

| Persona | Profile |
|---|---|
| **Weekend Luxury Browser** | High income, low visit frequency, high spend per visit, fashion & electronics focus |
| **Weekday Practical Shopper** | Mid income, high frequency, consistent grocery & essentials spend |
| **High-Frequency Deal Seeker** | Price-sensitive, very high visit frequency, promotional offer driven |
| **Occasional Leisure Visitor** | Young, sporadic visits, food court and entertainment focus |

---

## 🔑 Key Takeaways

- K-Means on behavioural + demographic features produces distinct, commercially actionable segments
- Persona naming and characterisation critical for business adoption of clustering outputs
- 78% sales uplift demonstrates direct commercial value of data-driven segmentation over generic retail strategy
- Silhouette score validation essential for selecting cluster count that produces genuinely distinct segments

---

## 🛠️ Tech Stack

`Python` `scikit-learn` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Plotly`

---

## 👩‍💻 Author

**Arpita Paul** · Senior Data Scientist · *From Seismology to GenAI 🚀*

[![GitHub](https://img.shields.io/badge/GitHub-ArpitaAI--collab-black?style=flat-square&logo=github)](https://github.com/ArpitaAI-collab)
