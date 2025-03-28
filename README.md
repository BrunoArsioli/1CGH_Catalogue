# 1CGH Catalogue Repository

**Welcome to the 1CGH Catalogue Repository!**

This repository hosts the **First Cosmic Gamma-ray Horizon (1CGH) catalogue**, a dataset created based on 16 years of Fermi-LAT observations, from August 2008 to August 2024. 

### **About the 1CGH Catalogue**

The **1CGH catalogue** aims to enhance our understanding of the transparency of the universe to gamma-rays and facilitate future studies of the extragalactic background light (EBL) by listing sources detected above 10 GeV. The 1CGH provides a comprehensive redshift characterization of these sources, offering improved reliability by tracking the quality of reported redshift values. It represents a comprehensive collection of blazars and blazar candidates, including:

- **2791 gamma-ray sources** detected above 10 GeV.
- **525 sources** experiencing moderate to severe gamma-ray attenuation in the largest energy bin, corresponding to an EBL optical depth of tau > 0.1.
- **62 new gamma-ray detections**, previously unreported in Fermi-LAT catalogues.

The catalogue includes extensive metadata, such as:

- **Source names, coordinates (R.A. and Dec.)**, and **detection significance (TS values)**.
- **Photon data** for the highest energy bins, including the **mean energy of the four highest-energy photons** associated with each source.
- **Redshift information**: We performed an extensive literature review to improve redshift characterization, introducing the `z-flag` system to classify spectroscopic, photometric, and lower-limit redshift estimates.

### **Content of the Repository**

- **First\_Cosmic\_GammaRay\_Horizon\_Catalogue\_1CGH_V1.fits**: The core data file containing the information about all sources in the 1CGH catalogue, including key metrics such as RA, Dec, TS value, redshift (`z`), and photon data.
- **`README.md`**: This document, providing an overview of the repository, data descriptions, and intended use.
- **`Data Description.md`**: A detailed explanation of the columns in the 1CGH catalogue.
- **`Figures`**: A folder containing key figures from the paper, such as the **cosmic gamma-ray horizon plots** showing the relationship between highest-energy photons and redshift.

### **Citation**

If you make use of the data in your research, please cite the corresponding publication:

*Arsioli, B., et al. (2024). Mapping the Cosmic Gamma-ray Horizon: The 1CGH Catalog of Fermi-LAT detections above 10 GeV. ******************[arXiv](https://arxiv.org/abs/2411.18431)******************[:2411.18431](https://arxiv.org/abs/2411.18431)*

### **Data Use Policy**

This dataset is made available under the **CC BY** license. Users are free to share and adapt the material, provided appropriate credit is given. For more information, see the [LICENSE](LICENSE.md) file.

### **Acknowledgements**

We acknowledge the **Fermi-LAT Collaboration** for maintaining a publicly available mission database, which has enabled the creation of the 1CGH catalogue. We also thank all contributors and researchers who have enriched the extensive literature on blazars and gamma-ray observations.

### **Contact**

For questions, suggestions, or collaborations, please contact **Bruno Arsioli** 

### **Disclaimer**

The 1CGH catalogue will be made available in the **VizieR** repository. 

Necessary updates based on community feedback and ongoing data reviews will be describe in this living GitHub repositore.

