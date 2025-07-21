# Trade-Wars-and-Global-Slowdown-How-Trump-s-Tariffs-Risked-a-Worldwide-Recession
# Trade Wars and Global Slowdown: How Trump's Tariffs Risked a Worldwide Recession
This repository explores the economic impact of U.S. tariffs on GDP and recession risk using Structural Equation Modeling (SEM). The project evaluates how protectionist policies, particularly those introduced during the 2018 and 2025 trade wars between the U.S. and China, influenced key macroeconomic indicators. It features two main SEM frameworks:

GDP Slowdown Analysis: Assesses how tariff shocks influence sectoral output and GDP.
Recession Risk Modeling via Yield Curve Behavior: Evaluates how tariffs flatten the yield curve, a well-known recession indicator.
Both models use publicly available macroeconomic datasets and are structured using preprocessed variables for empirical clarity.

📁 Project Structure:



<img width="851" height="282" alt="image" src="https://github.com/user-attachments/assets/de886f3f-0df7-4383-b260-0eab5fe9c49e" />


📉 GDP Slowdown SEM Model:
This SEM model explores how the shocks introduced by tariffs (both in price and revenue) indirectly and directly impact GDP through intermediate effects on sectoral output. The model provides insight into transmission channels and relative variable significance.

Latent Constructs
Tariff Policy Shock: Proxy for protectionist pressure, constructed from tariff revenue, import prices, and real imports.
Sectoral Output Decline: Captures macroeconomic slowdown through real GDP and import volume.
GDP Growth: Ultimate endogenous indicator representing economic health.
Model Equations
Measurement Model:
Tariff_Shock =~ Tariff_Revenue + Real_Imports + Import_Price
Sector_Output =~ Real_GDP + Real_Imports
GDP =~ Real_GDP
Structural Model:

Sector_Output ~ Tariff_Revenue + Real_Imports + Import_Price
GDP ~ Tariff_Revenue + Real_Imports + Import_Price + Sector_Output

<img width="863" height="507" alt="image" src="https://github.com/user-attachments/assets/1ab85b9f-8a2e-4a61-bf41-44999e620029" />


Interpretation: The dominant explanatory variable for GDP is sectoral output, which acts as a mediator between tariffs and growth. Direct tariff effects are statistically minor, but they significantly influence intermediate channels.

🔻 Recession Risk Model: Yield Curve SEM:
This model estimates how key macroeconomic indicators shift the U.S. yield curve slope — the difference between short- and long-term interest rates — often used to predict recessionary phases.
SEM Specification:
Yield_Curve = Real_GDP + Tariff_Revenue + Real_Imports

Model Output:


<img width="652" height="263" alt="image" src="https://github.com/user-attachments/assets/7118ed35-db25-472a-9501-d90871eacfe9" />




Interpretation
Tariff Revenue flattens the yield curve — consistent with increased recession risk.
Real GDP steepens the curve — a signal of strength.
Real Imports have no meaningful effect.
Conclusion: Increases in tariff revenue are statistically and economically significant in flattening the yield curve, indicating heightened market expectation of future economic contraction

⚖️ Comparative Analysis: 2018 vs 2025 US–China Trade Wars
This section contrasts the two major tariff episodes led by the U.S. under similar leadership styles, but drastically different policy tactics.

Aspect	2018 Trade War	2025 Trade War
Initiation Strategy	Gradual escalation with targeted goods	Immediate, universal tariffs on all imports
Peak US Tariff	25% on $250B of Chinese goods	145% in April 2025
China's Retaliation	25% on $110B US goods	125% briefly; 10% ongoing
Trade Coverage	US: $550B; China: $185B	US: 100% of imports; China: 100% of US goods
Truce Agreement	G20 (Argentina), Dec 2018 – 90-day ceasefire	Geneva, May 2025 – 90-day framework
Final Resolution	Phase One Deal, Jan 2020	London Framework, June 2025 (ongoing)
Strategic Comparison
2018: Characterized by phased imposition, with bilateral sector targeting and WTO engagement.
2025: More unilateral and immediate, resulting in broader international backlash and rapid yield curve inversion.
Both shared temporary truces and retaliatory measures but differed in economic aggression and scope.
