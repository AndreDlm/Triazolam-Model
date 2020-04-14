### 2.3.1	Dissolution and absorption

Dissolution of the immediate release tablet of triazolam was described by a Weibull function with the two parameters `Dissolution shape` and `Dissolution time (50% dissolved)` being fitted, together with the other parameters listed in [Section 2.1](#2.1 Modeling Strategy), to observed PK data to better match the observations. `Specific intestinal permeability (transcellular)` was also optimized together with the parameters listed in [Section 2.1](#2.1 Modeling Strategy).
### 2.3.2	Distribution

In the model, the `fraction unbound (plasma, reference value)` was set to 0.174 which is the reported mean value measured in 19 healthy male and female volunteers aged
20 to 45 years ([Friedman 1988](# 5 References)). This value is also the approximate average of all pooled values reported in several studies ([Jochemsen 1983](# 5 References), [Eberts 1981](# 5 References), [Greenblatt 1983](# 5 References),  [Friedman 1988](# 5 References), [Ochs 1987](# 5 References)). `Lipophilicity` was optimized together with the other parameters listed in [Section 2.1](#2.1 Modeling Strategy) to better match observed PK data. The observed PK data were found to be best described using the model for estimating intracellular-to-plasma partition coefficients according to the method by `Rodgers and Rowland` ([Rodgers 2005](# 5 References), [Rodgers 2006](# 5 References)). Cellular permeabilities were automatically calculated using the method `PK-Sim Standard` ([Open Systems Pharmacology Documentation](# 5 References)).  

### 2.3.3	Elimination

Triazolam is extensively metabolized via CYP3A to the two metabolites α-hydroxy-triazolam and 4-hydroxy-triazolam. In the model, these two biotransformation pathways were separately described via Michaelis-Menten kinetics. The `Km` values for each pathway were fixed to reported literature values, namely 74.2 µmol/L for the α-OH pathway and 305 µmol/L for the 4-OH pathway ([von Moltke 1996](# 5 References)). Together with the other parameters listed in [Section 2.1](#2.1 Modeling Strategy), the `kcat` values were optimized while keeping the ratio between both values constant (by selecting the option `Use as Factor`). The gene expression profile of CYP3A4 was loaded from the internal PK-Sim<sup>®</sup> database using the expression data quantified by RT-PCR ([Open Systems Pharmacology Documentation](# 5 References)).


