# 👩‍🎓 Impact of Female Human Capital on Children’s Educational Outcomes  

## 🎯 Project Overview  
Does maternal education matter more than other factors (urbanization, paternal education, wealth) in shaping children’s foundational learning outcomes?  
This project merges **multiple large-scale datasets** to quantify the causal relationship between female human capital and child education outcomes in India.  

---

## 📂 Dataset Integration  
Built a **435-district panel dataset** by merging:  
- **ASER (2011):** 600k+ household-level learning outcomes.  
- **SECC (2011):** Household socio-economic data.  
- **Census (2011):** Demographic and educational indicators.  
- **VIIRS Night Lights:** Proxy for urbanization and economic activity.  

---

## 🧮 Methodology  
- **Data Engineering:** Harmonized 600k+ household entries into district-level composites.  
- **Index Construction:** Built indices for household wealth, school infrastructure, and learning outcomes.  
- **Econometric Models:** Fixed Effects regressions, controlling for socio-economic and geographic factors.  
- **Visualization:** Heatmaps, boxplots, and spatial maps to uncover regional disparities.  

---

## 📊 Key Results  

### Effect of Maternal Education  

| Variable                  | Effect on Learning Outcomes |
|---------------------------|-----------------------------|
| **+1 year maternal education** | **+4.7 percentage points** ↑ |
| Paternal education        | Smaller effect              |
| Urbanization (night lights)| Negative correlation        |
| Wealth index              | Strongest predictor (β = 0.25***) |

- Maternal education outperformed paternal and urbanization factors as a predictor.  
- Household material well-being strongly correlated with foundational learning.  
- Challenged conventional assumption that urbanization → better schooling outcomes.  

---

## 💡 Impact & Insights  
- Provided **evidence-based policy directions** for tackling education inequality.  
- Highlighted need to **prioritize female education** as a high-impact intervention.  
- Exposed risks of relying solely on urbanization as a development proxy.  

---

## 🛠️ Tools & Skills  
- **R (dplyr, ggplot2, lfe, sf)** → regression analysis, mapping, visualization.  
- Econometrics: Fixed Effects, regression, correlation analysis.  
- Data wrangling & reproducible workflows (R Markdown).  

---

