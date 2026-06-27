# Migration, Remittances and Development Finance

> **Research Question:** To what extent do remittances act as an alternative source of development finance in remittance-dependent developing economies?

---

## Overview

Remittances are financial transfers sent by migrants to their home countries. In many developing economies, remittances represent a substantial share of national income and can often exceed official development assistance (foreign aid).

This project investigates which countries are most dependent on remittances and explores whether migration acts as an informal mechanism of international development by transferring resources directly to households in migrants' countries of origin.

---

## Data Sources

All data is retrieved from the **World Bank API** using the following indicators:

| Indicator Code | Description |
|---|---|
| `BX.TRF.PWKR.DT.GD.ZS` | Personal remittances received (% of GDP) |
| `BX.TRF.PWKR.CD.DT` | Personal remittances received (current US$) |
| `DT.ODA.ODAT.CD` | Net official development assistance received (current US$) |

---

## Results

<!-- Add your charts/graphs here once exported, e.g.: -->
<!-- ![Top Remittance-Dependent Countries](images/top_remittance_countries.png) -->
<!-- ![Nepal Remittances vs ODA Over Time](images/nepal_remittances_vs_oda.png) -->

- In **2023**, countries such as **Tonga, Tajikistan, Nepal, Honduras and El Salvador** received remittances equivalent to a substantial share of GDP.
- A case study of **Nepal** showed that remittance inflows increased significantly between 2000 and 2023, growing faster than official development assistance.
- Across Nepal, Honduras, El Salvador and Tajikistan, remittances **frequently exceed foreign aid** — in several cases by several times.

---

## Discussion

The findings suggest that migration may act as an informal mechanism of international development. Unlike foreign aid, remittances are private transfers that flow directly to households and can be used according to local needs and priorities.

However, remittance dependence also carries risks:
- **Economic vulnerability** - remittance inflows may fall if migrants lose employment in destination countries.
- **Brain drain** - emigration of skilled workers can reduce domestic human capital in sectors such as healthcare, education and engineering.

The findings therefore highlight only one aspect of migration's economic impact. A full assessment would need to weigh these costs against the financial benefits of remittances.

---

## Conclusion

The evidence indicates that remittances are a significant source of external finance and, in many remittance-dependent economies, exceed official foreign aid inflows. While remittances should not be viewed as a complete substitute for development assistance, they appear to play an increasingly important role in supporting economic development and household welfare in developing countries.

---

## Further Research

Future research could examine the wider economic effects of emigration by analysing indicators related to human capital and productivity — for example, whether countries with high skilled emigration experience slower GDP per capita growth, lower productivity, or reduced investment in healthcare and education.

---

## Technologies Used

- **Python 3**
- **pandas** — data manipulation and analysis
- **requests** — accessing the World Bank API
- **matplotlib** — data visualisation

## Installation

```bash
git clone https://github.com/yourusername/your-repo-name.git
pip install -r requirements.txt
```

## Usage

Open the notebook in Jupyter:

```bash
jupyter notebook your_notebook_name.ipynb
```
