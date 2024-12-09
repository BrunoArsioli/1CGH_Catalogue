# 1CGH Preliminary Catalogue Repository

**Welcome to the 1CGH Preliminary Catalogue Repository!**

This repository hosts the **preliminary version of the First Cosmic Gamma-ray Horizon (1CGH) catalogue**, a dataset created based on 16 years of Fermi-LAT observations, from August 2008 to August 2024. 

### **About the 1CGH Preliminary Catalogue**

The **1CGH catalogue** aims to enhance our understanding of the transparency of the universe to gamma-rays and facilitate future studies of the extragalactic background light (EBL) by listing sources detected above 10 GeV. The 1CGH provides a comprehensive redshift characterization of these sources, offering improved reliability by tracking the quality of reported redshift values. It represents a comprehensive collection of blazars and blazar candidates, including:

- **About 2900 gamma-ray sources** detected above 10 GeV.
- **About 520 sources** experiencing moderate to severe gamma-ray attenuation in the largest energy bin, corresponding to an EBL optical depth of tau > 0.1.
- **About 70 new gamma-ray detections**, previously unreported in Fermi-LAT catalogues.

This **preliminary version** serves as a first step to make the dataset publicly accessible for the research community, providing an opportunity for initial exploration and further collaborations. The catalogue includes extensive metadata, such as:

- **Source names, coordinates (R.A. and Dec.)**, and **detection significance (TS values)**.
- **Photon data** for the highest energy bins, including the **mean energy of the four highest-energy photons** associated with each source.
- **Redshift information**: We performed an extensive literature review to improve redshift characterization, introducing the `z-flag` system to classify spectroscopic, photometric, and lower-limit redshift estimates.

### **Content of the Repository**

- **1CGH\_Preliminary\_Catalogue.ascii**: The core data file containing the information about all sources in the 1CGH catalogue, including key metrics such as RA, Dec, TS value, redshift (`z`), and photon data.
- **`README.md`**: This document, providing an overview of the repository, data descriptions, and intended use.
- **`Data Description.md`**: A detailed explanation of the columns in the 1CGH catalogue.
- **`Figures`**: A folder containing key figures from the paper, such as the **cosmic gamma-ray horizon plots** showing the relationship between highest-energy photons and redshift.

### **Citation**

If you make use of the data in your research, please cite the corresponding publication:

*Arsioli, B., et al. (2024). Mapping the Cosmic Gamma-ray Horizon: The 1CGH Catalog of Fermi-LAT detections above 10 GeV. ******************[arXiv](https://arxiv.org/abs/2411.18431)******************[:XXXXX](https://arxiv.org/abs/2411.18431)*

### **Data Use Policy**

This dataset is made available under the **CC BY** license. Users are free to share and adapt the material, provided appropriate credit is given. For more information, see the [LICENSE](LICENSE.md) file.

### **Acknowledgements**

We acknowledge the **Fermi-LAT Collaboration** for maintaining a publicly available mission database, which has enabled the creation of the 1CGH catalogue. We also thank all contributors and researchers who have enriched the extensive literature on blazars and gamma-ray observations.

### **Contact**

For questions, suggestions, or collaborations, please contact **Bruno Arsioli** 

### **Disclaimer**

This is a **preliminary version** of the 1CGH catalogue, and as such, updates and refinements are expected. The final version will be made available in the **VizieR** repository and include any necessary updates based on community feedback and ongoing data reviews.

