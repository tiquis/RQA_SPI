# RQA_SPI

Recurrence Quantification Analysis (RQA) and Cross-Recurrence / Joint-Recurrence Plots (CRP/JRP) applied to regional SPI-12 drought series for Zacatecas, Mexico.

This notebook explores whether Recurrence Quantification Analysis (RQA) and Cross/Joint Recurrence Plots (CRP/JRP) provide information complementary to that already obtained with MF-DFA across the four physiographic regions of Zacatecas (Semi-arid, Highlands, Mountains, Canyons).

## Contents

- `RQA_SPI_Zacatecas_EN.ipynb` — full analysis notebook (Google Colab-ready): embedding parameter selection (AMI/FNN), Theiler-window-corrected RQA measures, Cross-Recurrence F-synchronization between regions, and sliding-window synchronization analysis around documented drought events (1996, 2011, 2012, 2021, 2023), with multiple-comparison correction (Bonferroni / Benjamini-Hochberg FDR).
- `manuscript/` — LaTeX manuscript in progress (target journal: *Climate*, MDPI).

## Data

The notebook expects the regional SPI-12 series (`regional_SPI12.csv`, 709 months, December 1965–December 2024) produced by the companion MF-DFA project. Data are not redistributed in this repository; point the notebook's `INPUT_CSV` variable to your own copy (see the notebook's data-loading section for details and verification checks).

## Related work

- Companion manuscript: Multifractal Detrended Fluctuation Analysis (MF-DFA) of Regional SPI Series in North-Central Mexico (under review, *Atmosphere*, MDPI).
- Methodological references: Marwan et al. (2007), *Phys. Rep.*; Semeraro et al. (2020), *Remote Sens.*; Theiler (1986), *Phys. Rev. A*.

## Author

Rafael Magallanes-Quintanar — Universidad Autónoma de Zacatecas, Unidad Académica de Ingeniería Eléctrica, Programa de Ingeniería en Computación.

## License

MIT License — see [LICENSE](LICENSE).
