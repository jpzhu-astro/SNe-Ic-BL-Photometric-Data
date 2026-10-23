# SNe Ic-BL Photometric Data — Zhu & Zhang (2026)

To facilitate their use by the astronomical community, we make publicly available the photometric data of broad-lined Type Ic supernovae (SNe Ic-BL) compiled and used in Zhu & Zhang, 2026, ApJ, 1007, 35 [https://doi.org/10.3847/1538-4357/ae84b3](https://doi.org/10.3847/1538-4357/ae84b3). These data are freely available for research purposes.

## Data Format

Unless otherwise specified in an individual `Readme.txt` file, the data are stored in files `named SN_name_band.txt` and organized into three columns:

1. **Column 1:** Observation times in the observer frame, with an arbitrary reference epoch.
2. **Column 2:** Observed magnitudes without any extinction correction.
3. **Column 3:** Magnitude uncertainties (error bars).

## Important Notes on PTF/iPTF Data

Since the original photometric data from the PTF/iPTF were not publicly accessible to us, these data were manually digitized from the figures presented in Taddia et al. 2017, A&A, 621, A71.

Due to significant overlap among some data points in the published figures, we cannot guarantee the complete accuracy of the digitized PTF/iPTF photometry. For data points whose error bars could not be reliably identified, we conservatively adopted a relatively large uncertainty of 0.1 mag.

Users should therefore exercise caution when interpreting or fitting these digitized data.

## Acknowledgments and Citations

If you use these data in your research, please acknowledge **Jin-Ping Zhu and Bing Zhang** for compiling and publicly sharing the SNe Ic-BL photometric data and cite the following paper:

**Zhu, J.-P., & Zhang, B. (2026), ApJ, 1007, 35.** [https://doi.org/10.3847/1538-4357/ae84b3](https://doi.org/10.3847/1538-4357/ae84b3)

BibTeX citation:

```bibtex
@ARTICLE{2026ApJ..1007...35Z,
       author = {{Zhu}, Jin-Ping and {Zhang}, Bing},
        title = "{Magnetar Engines in Broad-lined Type Ic Supernovae and a Unified Picture for Magnetar-powered Stripped-envelope Supernovae}",
      journal = {The Astrophysical Journal},
         year = 2026,
        month = aug,
       volume = {1007},
       number = {1},
          eid = {35},
        pages = {35},
          doi = {10.3847/1538-4357/ae84b3},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2026ApJ..1007...35Z}
}
```

Some of the Zwicky Transient Facility (ZTF) photometric data were obtained through the **ZTF forced-photometry service**. Users of these data should follow the acknowledgment and citation guidelines described in Section 1 of the [ZTF Forced Photometry Documentation](https://irsa.ipac.caltech.edu/data/ZTF/docs/ztf_forced_photometry.pdf).

## Data Sources and References

For the information (redshift and extinction) and references for each SN, please refer to **Table 1 of Zhu & Zhang (2026)**.

For convenience, the relevant references have also been compiled in the accompanying reference list. These references include: [1] A. Clocchiatti et al. (2011); [2] R. J. Foley et al. (2003); [3] J. Deng et al. (2005); [4] S. Valenti et al. (2008); [5] D. Malesani et al. (2004); [6]S. Taubenberger et al. (2006); [7] D. K. Sahu et al. (2009); [8] G. Pignata et al. (2011); [9] Z. Cano et al. (2011); [10] A. Corsi et al. (2011) and F. Taddia et al. (2019); [11] F. Taddia et al. (2019); [12] E. S. Walker et al. (2014) and F. Taddia et al. (2019); [13] V. L. Toy et al. (2016) and A. A. Volnova et al. (2017); [14] D.K.Sahuetal.(2018);[15] Z.Canoetal.(2015);[16] A.Gangopadhyayetal.(2020);[17] S.J.Prenticeetal.(2018);[18] Z.Canoetal.(2017);[19] L.Izzoetal. (2019); [20] S. J. Prentice et al. (2019); [21] G. P. Srinivasaragavan et al. (2024); [22] A. Rossi et al. (2026); [23] S. Anand et al. (2024) and G. P. Srinivasaragavan et al. (2024); [24] ZTF forced-photometry service (F. J. Masci et al. 2019); [25] M. Mousa et al. (2025); and [26] G. P. Srinivasaragavan et al. (2026).

## License

The original compilation and documentation in this repository are made available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/), to the extent that the authors hold the applicable rights.

Third-party photometric data remain subject to their original usage and attribution requirements. Users should acknowledge and cite the original data sources as appropriate.
