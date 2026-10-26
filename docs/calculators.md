# Methodology & Mathematical Formulations

Chemistrycal implements rigorous scientific standards derived from IUPAC guidelines and peer-reviewed materials characterization literature.

## 1. Solution Molarity and Hydrate Compensation
When preparing standard solutions, crystal hydration weights significantly alter required balance masses. The master equation integrated into the [Molarity Calculator](https://chemistrycal.com/molarity) is defined as:

$$m = \frac{C \times V \times MW_{\text{hydrated}}}{\text{Purity} \times 1000}$$

## 2. PXRD Scherrer Crystallite Sizing
To determine crystallite domain dimensions from X-ray diffraction patterns via our [PXRD Scherrer Calculator](https://chemistrycal.com/scherrer), raw peak broadening is corrected for instrumental optics using Gaussian deconvolution:

$$\beta_{\text{sample}} = \sqrt{\beta_{\text{obs}}^2 - \beta_{\text{inst}}^2}$$

$$\tau = \frac{K \cdot \lambda}{\beta_{\text{sample}} \cos(\theta)}$$

---
*For live interactive solvers, visit the main portal at [Chemistrycal](https://chemistrycal.com).*
