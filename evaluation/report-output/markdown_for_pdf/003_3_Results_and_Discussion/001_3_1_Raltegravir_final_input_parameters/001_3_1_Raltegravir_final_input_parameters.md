## 3.1 Raltegravir final input parameters
The compound parameter values of the final raltegravir PBPK model are illustrated below.




# Formulation: chewable tablet

Type: Weibull
## Parameters

Name                             | Value                | Value Origin             |
-------------------------------- | -------------------- | ------------------------ |
Dissolution time (50% dissolved) | 1.0000049774E-05 min | Parameter Identification |
Lag time                         | 0 min                |                          |
Dissolution shape                | 0.050078869          | Parameter Identification |
Use as suspension                | Yes                  |                          |

# Formulation: filmcoated tablet (original Merck formulation)

Type: Weibull
## Parameters

Name                             | Value      | Value Origin             |
-------------------------------- | ---------- | ------------------------ |
Dissolution time (50% dissolved) | 500 min    | Parameter Identification |
Lag time                         | 0 min      |                          |
Dissolution shape                | 0.03536656 | Parameter Identification |
Use as suspension                | Yes        |                          |

# Compound: Raltegravir

## Parameters

Name                                             | Value                 | Value Origin                           | Alternative | Default |
------------------------------------------------ | --------------------- | -------------------------------------- | ----------- | ------- |
Solubility table                                 | 40 mg/l               | Publication-In Vitro-Moss 2013 Table 2 | Moss 2013   | True    |
Lipophilicity                                    | 0.58 Log Units        | Parameter Identification               | Moss 2012   | True    |
Fraction unbound (plasma, reference value)       | 0.17                  | Publication-In Vitro-Laufer 2009       | Measurement | True    |
Specific intestinal permeability (transcellular) | 2.8481843854E-07 cm/s | Parameter Identification               | Fit         | True    |
F                                                | 1                     | Publication-Other-Drugbank.ca          |             |         |
Is small molecule                                | Yes                   |                                        |             |         |
Molecular weight                                 | 444.4163 g/mol        | Publication-Other-Drugbank.ca          |             |         |
Plasma protein binding partner                   | Albumin               |                                        |             |         |
## Calculation methods

Name                    | Value               |
----------------------- | ------------------- |
Partition coefficients  | Rodgers and Rowland |
Cellular permeabilities | PK-Sim Standard     |
## Processes

### Systemic Process: Glomerular Filtration-Kassahun 2007

Species: Human
#### Parameters

Name         | Value | Value Origin                       |
------------ | -----:| ---------------------------------- |
GFR fraction |     1 | Publication-In Vitro-Kassahun 2007 |
### Metabolizing Enzyme: UGT1A1-Kassahun 2007

Molecule: UGT1A1
#### Parameters

Name                               | Value                                 | Value Origin                       |
---------------------------------- | ------------------------------------- | ---------------------------------- |
In vitro Vmax for liver microsomes | 2.7351231632 nmol/min/mg mic. protein | Parameter Identification           |
Km                                 | 99 µM                                 | Publication-In Vitro-Kassahun 2007 |
### Metabolizing Enzyme: UGT1A9-Kassahun 2007

Molecule: UGT1A9
#### Parameters

Name                               | Value                                 | Value Origin                       |
---------------------------------- | ------------------------------------- | ---------------------------------- |
In vitro Vmax for liver microsomes | 1.6287812095 nmol/min/mg mic. protein | Parameter Identification           |
Km                                 | 296 µM                                | Publication-In Vitro-Kassahun 2007 |

# Formulation: Weibull (granules)

Type: Weibull
## Parameters

Name                             | Value                | Value Origin             |
-------------------------------- | -------------------- | ------------------------ |
Dissolution time (50% dissolved) | 0.00010000047426 min | Parameter Identification |
Lag time                         | 0 min                |                          |
Dissolution shape                | 0.0654456264         | Parameter Identification |
Use as suspension                | Yes                  |                          |

# Formulation: Weibull (lactose formulation)

Type: Weibull
## Parameters

Name                             | Value              | Value Origin             |
-------------------------------- | ------------------ | ------------------------ |
Dissolution time (50% dissolved) | 2.30152527E-10 min | Parameter Identification |
Lag time                         | 0 min              |                          |
Dissolution shape                | 0.0389537131       | Parameter Identification |
Use as suspension                | Yes                |                          |

