# Geopolitical_Risk_Index
This project develops a **Geopolitical Risk Index (GRI)** —a data-driven framework that systematically measures:

1. Core risk drivers: **Political stability, rule of law and corruption control** weighted by their demonstrated impact on oil production continuity.
2. Market exposure: Country risk scores scaled to actual oil production volumes, translating vulnerabilities into millions of barrels per day (bpd) at risk.

By integrating these metrics, the GRI enables energy firms to optimize sourcing, trading and investment strategies with actionable, quantifiable insights into geopolitical risk.

## 1. Problem Statement
The energy industry is acutely vulnerable to geopolitical disruptions. According to a report published by the Energy Information Administration (2024), sudden supply shocks frequently trigger price swings exceeding 30% within weeks. Traditional risk assessments remain reactive, relying on qualitative analyst reports that fail to quantify how governance fundamentals (political stability, the rule of law and corruption control) impact production stability.

## 2. Data
Data is sourced from reputable institutions like:
- World Bank- Worldwide Governance Indicators (WGI)
- Energy Institute- Statistical Review of World Energy

## 3. Index Components
- **Oil Production** - Measured in barrels per day (bbl/day) to weigh countries by production scale.
- **Political Stability**- Reflects the likelihood of political instability and/or politically-motivated violence.
- **Rule of Law**- Measures confidence in adherence to the rules of society, including the quality of contract enforcement, property rights and the courts.
- **Control of Corruption** Captures perceptions of the extent to which public power is exercised for private gain.

## 4. Methodology
- **Data Normalization**: Governance indicators are normalized to a common scale of 0–100.
- **Weighting**: Governance indicators are averaged into a composite governance score based on their importance
   - **Political Stability**- 40%
   - **Rule of Law**-30%
   - **Control of Corruption**-30%
     
**Risk Index Calculation**: 
   - Higher GRI = Higher geopolitical risk from an oil supply standpoint.

 ## 5. Key Insights
- 32.7% of global oil production originates from high-risk countries. A significant portion of global supply remains vulnerable to disruptions, reinforcing the need for diversification in energy sourcing.

- **Highest_Risk_Producers:**
  
| country            |   oil_production_kbd |   composite_risk |
|:-------------------|---------------------:|-----------------:|
| Iraq               |                 2120 |          76.1759 |
| Nigeria            |                 2023 |          64.9497 |
| Venezuela, RB      |                 3447 |          59.9598 |
| Russian Federation |                11679 |          59.7176 |
| Angola             |                 1150 |          58.7761 |
| Algeria            |                 1465 |          57.7518 |
| Iran, Islamic Rep. |                 3850 |          56.6008 |
| Libya              |                 1807 |          50.7766 |
| Kazakhstan         |                 1609 |          50.0883 |
| Mexico             |                 3592 |          49.4248 |

-**Top Stable High Producers:**
| country              |   oil_production_kbd |   composite_risk |
|:---------------------|---------------------:|-----------------:|
| Norway               |                 2024 |          12.3117 |
| Canada               |                 5647 |          18.1363 |
| United Kingdom       |                  715 |          22.2328 |
| Qatar                |                 1783 |          26.8426 |
| United Arab Emirates |                 4016 |          27.0448 |

- OPEC is significant because it collectively manages a huge portion of global oil supply, giving its members the ability to influence global energy prices and international economic trends.

- A time-series(1996-2024) comparison reveals: OPEC risk scores have worsened relative to non-OPEC producers, driven by:

- Venezuela’s collapse (sharp deterioration post-2014)
   - Libya’s instability (post-Gaddafi volatility)
   - Iran’s fluctuating risk (impact of sanctions and protests)
   - Non-OPEC producers (e.g., U.S., Canada, Norway) have maintained lower risk scores due to stable governance and regulatory frameworks.

- Key Trend: OPEC’s reliance on high-risk producers has increased supply-side vulnerabilities over the past decade.









