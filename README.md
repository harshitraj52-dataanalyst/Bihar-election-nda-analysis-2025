# Bihar Assembly Election 2025  
## Analysis of 41 NDA-Lost Constituencies Across Electoral and Socio-Economic Parameters

---

## Project Context & Motivation

This project is a post-election analytical study of the Bihar Assembly Election 2025, focusing on constituencies where the National Democratic Alliance (NDA) was defeated despite a statewide electoral wave and a more consolidated alliance compared to the previous two election cycles.

The objective of this analysis is not electoral prediction, but diagnostic evaluation. It examines the association between polling behaviour, electoral patterns, and selected socio-economic parameters in these constituencies to better understand the nature of electoral outcomes and structural challenges observed in 2025.

---

## Research Questions

The analysis is guided by the following research questions:

1. Is there any observable association between selected socio-economic indicators and NDA vote share in the constituencies lost in the 2025 Bihar Assembly election, particularly in the context of welfare interventions such as the CM Mahila Rojgar Yojana?

2. What types of seats constitute the 41 NDA-lost constituencies when classified on the basis of historical electoral performance across the 2015, 2020, and 2025 elections?

3. Did voter turnout levels play a role in NDA losses?

4. Is female socio-economic participation (such as literacy and workforce participation) more relevant to electoral outcomes than mere demographic presence?

5. Do regional or geo-cultural patterns emerge among the constituencies lost by the NDA?

---

## Data Sources

The analysis is based on the following data sources:

1. District-level socio-economic data from the Census of India (District Census Handbook).

2. Constituency-level election results for the Bihar Assembly Elections of 2015, 2020, and 2025, sourced from the Election Commission of India and IndiaVotes.com.

3. District-level electricity (energy) consumption data (MU), sourced from the Bihar Economic Survey 2024–25.

4. Derived categorical variables for voter turnout levels, urbanisation status, education levels, and seat typology, created through post-processing and segmentation of raw numerical data for analytical comparison.

---

## Methodology

- District-level socio-economic data was mapped to assembly constituencies to enable constituency-level analysis.

- Seats were classified into four categories:Chronic Weak, Swing, Core Collapse, and Early Decline, based on the structural vote base and past electoral performance of the NDA across the 2015, 2020, and 2025 elections.

- Continuous socio-economic variables were categorised into four bands: Very Low, Low, Moderate, and High.

- Scatter plots were used for exploratory correlation checks between socio-economic indicators and electoral outcomes.

- Stacked bar charts and categorical summaries were prioritised for dashboard presentation to highlight structural patterns.

- The absence of correlation was treated as a valid analytical outcome and incorporated into the interpretation.

---

## Key Observations

- Out of the 41 NDA-lost constituencies, 28 fall under the Chronic Weak seat category, indicating long-term structural challenges rather than short-term electoral fluctuations.

- Approximately 71% of the NDA-lost constituencies recorded very high voter turnout (≈70%), suggesting competitive or opposition-driven mobilisation rather than voter apathy.

- Above-matric education levels beyond a certain threshold show a stabilising but non-linear association with NDA vote share, indicating diminishing returns rather than a linear relationship.

- Female literacy and female workforce participation display mixed and context-dependent patterns across seat types, rather than a uniform association with electoral outcomes.

- Among the bottom five NDA vote-share constituencies (within the lost seats), all exhibit low or very low levels of energy consumption, female literacy, and urbanisation.

- A total of 28 out of the 41 lost constituencies are concentrated in the regions of Seemanchal, Magadh, and Mithila, indicating regional clustering of electoral losses.

- Fifteen constituencies show a strong presence of a third front (more than 15% vote share), and all such constituencies recorded very high voter turnout.

- Eight out of these fifteen strong third-front constituencies are located in the Seemanchal region.

- Three out of the four Core Collapse seats experienced narrow electoral losses, and all three display relatively high female workforce participation alongside low urbanisation and low female literacy.

- Eleven of the fifteen strong third-front constituencies fall within the Chronic Weak seat category, indicating weak structural vote bases and limited grassroots organisational penetration.

- All constituencies where the NDA suffered heavy losses in terms of vote margin recorded high or very high voter turnout.

---

## Conclusions

- NDA losses in the Bihar Assembly Election 2025 cannot be clearly attributed to any single socio-economic determinant, indicating the absence of a uniform explanatory variable across all lost constituencies.

- Structural seat history plays a stronger role in explaining electoral outcomes than short-term socio-economic or electoral fluctuations, particularly in constituencies classified as Chronic Weak.

- The high prevalence of very high voter turnout among NDA-lost constituencies suggests that losses largely occurred in politically competitive environments, reflecting intensified opposition mobilisation rather than widespread voter disengagement.

- This pattern is especially evident in three of the four Core Collapse seats and five of the seven Swing seats, where very high turnout coincided with narrow margins of defeat, indicating mobilisation asymmetry rather than erosion of the NDA’s underlying structural vote base.

- In contrast, constituencies characterised by long-term electoral losses and strong third-front presence point toward persistent structural weaknesses, including limited organisational depth and constrained grassroots penetration.

- Regional clustering of losses across Seemanchal, Magadh, and Mithila highlights the relevance of region-specific political dynamics, underscoring that electoral challenges are not evenly distributed across the state.

- Demographic presence alone is insufficient to explain voting behaviour without considering levels of participation, mobilisation intensity, and competitive political context.

- Socio-economic variables interact with electoral outcomes conditionally, with their relevance varying by seat type and regional context rather than operating in a linear or uniform manner.

- In Core Collapse constituencies, losses are observed in areas marked by relatively high female workforce participation and low urbanisation, suggesting the continued presence of a rural female voter base and indicating that electoral outcomes in these seats are shaped more by mobilisation dynamics than by demographic absence.

---

## Scope and Limitations

This study is subject to the following limitations:

- District-level socio-economic indicators may not fully capture intra-constituency variations within assembly seats.

- Correlation-based analysis does not establish causation and should be interpreted as indicative rather than deterministic.

- The analytical focus on NDA-lost constituencies limits direct comparative inference with NDA-won seats.

- Findings are contextual to the political landscape of Bihar and the 2025 Assembly election cycle.

- Several socio-economic indicators are sourced from the Census of India 2011 District Census Handbook, which may not fully reflect current socio-economic conditions.

---

## Repository Structure

The repository is organised as follows:

- /data/ – Contains source datasets and processed data files used for analysis.

- /dashboard/ – Contains the Power BI dashboard file (.pbix) used for visualisation.

- README.md – Provides an overview of the project, methodology, observations, and conclusions.

---

## Usage Notes

This repository is intended for analytical and academic use.  
The dashboard and findings should be interpreted as diagnostic insights rather than prescriptive recommendations.
