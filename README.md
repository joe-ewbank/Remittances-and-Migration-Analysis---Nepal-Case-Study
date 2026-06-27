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

In 2023, countries such as Tonga, Tajikistan, Nepal, Honduras and El Salvador received remittances equivalent to a substantial share of GDP.

![Remittances vs Foreign Aid by Country](images/remittance_to_foreign_aid.png)

![Total Remittances vs Foreign Aid](images/remittances_vs_foreign_aid_total.png)

### Case Study: Nepal

Nepal provides a clear example of the growing importance of remittances as a source of development finance.

![Nepal Remittances as % of GDP](images/nepal_remittances_as_gdp.png)

![Nepal Remittances Received Over Time](images/nepal_remittances_received.png)

Remittances grew faster than official development assistance over the same period and became a major source of external finance.

![Nepal Remittances vs Aid](images/nepal_remittances_vs_aid.png)

![Nepal Remittances Relative to Aid](images/nepal_remittances_relative_to_aid.png)

---

## Discussion

The findings suggest that migration may act as an informal mechanism of international development. Unlike foreign aid, remittances are private transfers that flow directly to households and can be used according to local needs and priorities.

However, remittance dependence also carries risks:
- **Economic vulnerability** — remittance inflows may fall if migrants lose employment in destination countries.
- **Brain drain** — emigration of skilled workers can reduce domestic human capital in sectors such as healthcare, education and engineering.

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
