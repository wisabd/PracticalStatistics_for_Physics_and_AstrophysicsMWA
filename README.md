## Description
- These are tutorial projects from the graduate course Practical Statistics for Physics and Astrophysics at University of Bologna taught by Prof. Metcalf

## Statistical Summary projects
- Bayesian parameter estimation: Bayesian parameter estimation is a statistical method that uses Bayes' theorem to update the probability of a hypothesis (e.g., the strength and width of a spectral line) as more evidence (e.g., observational data) becomes available
- 

## Datasets used
- For linear regression task, the dataset in this tutorial is stored in a FITS (Flexible Image Transport System) file named k_nmf_derived.newdefault.fits. The dataset contains template spectra, which are rest-frame galaxy spectra used for comparison. These templates represent different types of galaxies or stellar populations.
<p align="left">
  <img width="242" alt="Screenshot 2025-02-24 125343" src="https://github.com/user-attachments/assets/477f9de0-35ef-4e60-9c25-755e5f143d97" />
</p>
- For the photometric redshift tutorial the dataset is as following:

| Column Name              | Description |
|--------------------------|-------------|
| `id`                     | Unique identifier for the galaxy |
| `spectroscopic redshift` | Measured redshift (used as the target variable) |
| `fluxes (ugriz)`         | Observed flux values in **five photometric bands** (u, g, r, i, z) |
| `magnitudes (ugriz)`     | Corresponding magnitudes in the **same five bands** |

- Bayesian parameter estimation to measure the strength and width of a spectral line. Wavelength is on the x-axis(Represents the position in the spectrum, typically in angstroms (Å) or nanometers (nm)). Flux is on the y-axis(The observed intensity of light at each wavelength). Sigma is used as the error bars for the flux (The standard deviation (uncertainty) of the flux measurement at each wavelength).
  <img width="227" alt="image" src="https://github.com/user-attachments/assets/71d0f73e-2da4-47e5-a55a-03b9cd8a7b65" />




## Technologies used
- matplotlib, numpy, pandas, astropy.io
  
## Screenshots of Plots generated

<img width="212" alt="Screenshot 2025-02-24 073829" src="https://github.com/user-attachments/assets/407a530a-2dfa-4a25-b010-493805dc240c" />
<img width="471" alt="Screenshot 2025-02-24 073433" src="https://github.com/user-attachments/assets/aa6bef9e-f80c-44f3-8d08-4e1b94b35145" />
<img width="223" alt="Screenshot 2025-02-24 073456" src="https://github.com/user-attachments/assets/c888e14d-cc1a-45b5-a0d5-855a074b9677" />
<img width="239" alt="Screenshot 2025-02-24 073730" src="https://github.com/user-attachments/assets/12f165a9-a3ae-48b0-8c13-360d870ae2c6" />
