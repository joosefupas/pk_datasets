# Theoph Dataset

## Description

The `Theoph` dataset contains 132 observations of an experiment on the pharmacokinetics of theophylline. The dataset is structured with 5 columns, providing detailed information on the subjects' response to theophylline, a drug commonly used for the treatment of respiratory diseases like asthma.

## Usage

```r
data(Theoph)
```

# Format
The dataset is an object of class c("nfnGroupedData", "nfGroupedData", "groupedData", "data.frame") and includes the following columns:

- Subject: An ordered factor with levels 1 to 12 identifying the individual subjects. Ordering is based on increasing maximum concentration of theophylline observed.
- Wt: The weight of the subject in kilograms (kg).
- Dose: The dose of theophylline administered orally to the subject in milligrams per kilogram (mg/kg).
- Time: The time since drug administration when the sample was drawn, in hours (hr).
- conc: The concentration of theophylline in the sample, measured in milligrams per liter (mg/L).

# Details
The dataset was reported in a study by Dr. Robert Upton on the kinetics of theophylline. Serum concentrations were measured at 11 time points over 25 hours following oral administration. Analysis of these data can be found in literature from Boeckmann, Sheiner, and Beal (1994), Davidian and Giltinan (1995), and Pinheiro and Bates (2000), which employ a two-compartment open pharmacokinetic model.

# Source References
- Boeckmann, A. J., Sheiner, L. B., and Beal, S. L. (1994), "NONMEM Users Guide: Part V," NONMEM Project Group, University of California, San Francisco.
- Davidian, M., and Giltinan, D. M. (1995) "Nonlinear Models for Repeated Measurement Data," Chapman & Hall.
- Pinheiro, J. C., and Bates, D. M. (2000) "Mixed-effects Models in S and S-PLUS," Springer.

## See Also
For a self-starting model function for the analysis of this type of data, see SSfol.

