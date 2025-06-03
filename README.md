
# Digital Financial Inclusion: Building a Fintech Index for Africa
Digital Financial Inclusion Index for Africa
This is a subpraject of FINIA project that introduces a novel index designed to measure digital financial inclusion across African nations. The index evaluates the performance of digital finance by focusing on key components such as mobile technology infrastructure, investment in fintech, and user accessibility.


<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Purpose of the Index

This index was developed to:

- **Simplify complex data**: Condense multifaceted digital finance data into a single, comprehensible metric.
- **Track progress**: Monitor changes in digital financial inclusion over time.
- **Enable comparisons**: Identify leaders and laggards in digital finance adoption.

</div>



</div>

---

<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Components of the Index

- **Infrastructure**: Based on the [GSMA Mobile Connectivity Index](https://www.mobileconnectivityindex.com/).
- **Investment**: Fintech investment data sourced from [Crunchbase](https://www.crunchbase.com/), normalized by GDP.
- **Literacy**: Adult literacy rates from the [World Bank](https://data.worldbank.org/indicator/SE.ADT.LITR.ZS).

</div>



</div>

---

<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Methodology

1. **Data Collection** – From reliable sources like GSMA, Crunchbase, and the World Bank.  
2. **Feature Selection** – Indicators with strong relevance to digital financial inclusion.  
3. **Weighting** – Equal weights (1/3) for each component.  
4. **Validation** – Factor analysis, internal consistency checks, expert review.

### Mathematical Definition

The **Digital Financial Inclusion Index (DFI Index)** is calculated as the **geometric mean** of the three normalized components:

<p align="center">
  $$\text{DFI Index} = \frac{1}{3}\(\text{Infrastructure} + \text{Investment} + \text{Literacy}\)$$
</p>

> This approach ensures that low performance in any single component meaningfully affects the overall score.

</div>
<div style="flex: 1;">
  <img src="https://github.com/ntakirutimanapierre/FINIA/blob/main/Index%20Images/literacy.png" alt="Methodology Diagram" style="width:100%; border-radius: 8px;" />
</div>

<div style="flex: 1;">
  <img src="https://github.com/ntakirutimanapierre/FINIA/blob/main/Index%20Images/gsmaindex.png" alt="Methodology Diagram" style="width:100%; border-radius: 8px;" />
</div>

<div style="flex: 1;">
  <img src="https://github.com/ntakirutimanapierre/FINIA/blob/main/Index%20Images/combinationinvestment.png" alt="Methodology Diagram" style="width:100%; border-radius: 8px;" />
</div>
</div>

---

<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Key Findings

- **Top Performers (2023):**

   Seychelles (84%)
   South Africa (79%)
   Mauritius & Egypt (76%)

- **Lower Performers:**  
  Mali (36%)
  Somalia (39%)
  Democratic Republic of Congo (43%)

- Island nations and smaller populations adopt fintech more rapidly.  
- Countries with limited infrastructure and tight regulations lag behind.

</div>

<div style="flex: 1;">
  <img src="https://github.com/ntakirutimanapierre/FINIA/blob/main/Index%20Images/maps.png" alt="Digital Inclusion Map" style="width:100%; border-radius: 8px;" />
</div>

</div>

---

<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Recommendations

- **Supportive Policy** – Create regulatory environments that foster fintech innovation.
- **Infrastructure Investment** – Expand internet and mobile networks.
- **Monitoring** – Update index annually for data-driven policymaking.

</div>

<div style="flex: 1;">
  <img src="https://i.imgur.com/Gpr2B6P.png" alt="Recommendations Graphic" style="width:100%; border-radius: 8px;" />
</div>

</div>

---

<div style="display: flex; gap: 40px; align-items: flex-start; margin-bottom: 40px;">

<div style="flex: 1;">

## Acknowledgements

This project was made possible through the support and guidance of:

- [Edith Luhanga (CMU)](https://www.africa.engineering.cmu.edu/about/contact/directory/bios/luhanga-edith.html)
- [Ganesh Mani (CMU)](https://scholars.cmu.edu/11206-ganesh-mani)
- [Patrick McSharry (CMU)](https://engineering.cmu.edu/directory/bios/mcsharry-patrick.html)
- [Chimwemwe Chipeta (Wits)](https://www.wits.ac.za/people/academic-a-z-listing/c/chimwemwechipetawitsacza/)
- [Yves Mfitumukiza Ndayisaba (CMU)](https://www.linkedin.com/in/yves-mfitumukiza-ndayisaba/)
- [Pierre Ntakirutimana](https://www.linkedin.com/in/pierre-ntakirutimana-b784ba186/)

Funding was provided by the [Afritec Network](https://measuring-digital-financ-opoy9ek.gamma.site/)


For more detailed information, please refer to the full project presentation available at the [project website](https://measuring-digital-financ-opoy9ek.gamma.site/). 

---

## References

1. [GSMA Mobile Connectivity Index](https://www.mobileconnectivityindex.com/)  
2. [Crunchbase – Startup and Investment Data](https://www.crunchbase.com/)  
3. [World Bank – Literacy Rates](https://data.worldbank.org/indicator/SE.ADT.LITR.ZS)  
4. [AfriTec Network](https://afritec.carnegiemellon.africa/)
