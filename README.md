# Fault Analysis Database with Features (FADbF)

**Associated Tasks**: classification and regression

**Instances**: 168,000

**Attributes**: 128, including the two possible targets

**Additional Information**: this database comprises several attributes extracted from time series of fault simulations of a transmission line with 500 kV, 414 km, and 60 Hz. In total, we extracted 21 features separately for each of the three phases for both voltage and current waveforms along two post-fault cycles from a single terminal, resulting in 126 attributes (21 * 3 * 2 = 126) in addition to the two possible targets, i.e., fault type (classification task) and fault location (regression task). If desired, the fault type can also be used as a feature for the fault location task.

**Attribute list**:
|  Feature name  |  Role |  Type  |  Description  |
|  ------------  |  ---- |  ----  |  -----------  |
|  fault_type  | Target  |  Categorical  |  |
|  fault_location  | Target  |  Discrete  |  |
|  energy_phase_A_current  | Feature  |  Discrete  |  |
|  energy_phase_B_current  | Feature  |  Discrete  |  |
|  energy_phase_C_current  | Feature  |  Discrete  |  |
|  distance_phase_A_current  | Feature  |  Discrete  |  |
|  distance_phase_B_current  | Feature  |  Discrete  |  |
|  distance_phase_C_current  | Feature  |  Discrete  |  |
|  rms_phase_A_current  | Feature  |  Discrete  |  |
|  rms_phase_B_current  | Feature  |  Discrete  |  |
|  rms_phase_C_current  | Feature  |  Discrete  |  |
|  kurtosis_phase_A_current  | Feature  |  Discrete  |  |
|  kurtosis_phase_B_current  | Feature  |  Discrete  |  |
|  kurtosis_phase_C_current  | Feature  |  Discrete  |  |
|  skewness_phase_A_current  | Feature  |  Discrete  |  |
|  skewness_phase_B_current  | Feature  |  Discrete  |  |
|  skewness_phase_C_current  | Feature  |  Discrete  |  |
|  maxFrequency_phase_A_current  | Feature  |  Discrete  |  |
|  maxFrequency_phase_B_current  | Feature  |  Discrete  |  |
|  maxFrequency_phase_C_current  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_A_current  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_B_current  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_C_current  | Feature  |  Discrete  |  |
|  auc_phase_A_current  | Feature  |  Discrete  |  |
|  auc_phase_B_current  | Feature  |  Discrete  |  |
|  auc_phase_C_current  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_A_current  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_B_current  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_C_current  | Feature  |  Discrete  |  |
|  slope_phase_A_current  | Feature  |  Discrete  |  |
|  slope_phase_B_current  | Feature  |  Discrete  |  |
|  slope_phase_C_current  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_A_current  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_B_current  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_C_current  | Feature  |  Discrete  |  |
|  mean_phase_A_current  | Feature  |  Discrete  |  |
|  mean_phase_B_current  | Feature  |  Discrete  |  |
|  mean_phase_C_current  | Feature  |  Discrete  |  |
|  geometric_mean_phase_A_current  | Feature  |  Discrete  |  |
|  geometric_mean_phase_B_current  | Feature  |  Discrete  |  |
|  geometric_mean_phase_C_current  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_A_current  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_B_current  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_C_current  | Feature  |  Discrete  |  |
|  variance_phase_A_current  | Feature  |  Discrete  |  |
|  variance_phase_B_current  | Feature  |  Discrete  |  |
|  variance_phase_C_current  | Feature  |  Discrete  |  |
|  stdev_phase_A_current  | Feature  |  Discrete  |  |
|  stdev_phase_B_current  | Feature  |  Discrete  |  |
|  stdev_phase_C_current  | Feature  |  Discrete  |  |
|  median_phase_A_current  | Feature  |  Discrete  |  |
|  median_phase_B_current  | Feature  |  Discrete  |  |
|  median_phase_C_current  | Feature  |  Discrete  |  |
|  covariance_phase_A_B_current  | Feature  |  Discrete  |  |
|  covariance_phase_A_C_current  | Feature  |  Discrete  |  |
|  covariance_phase_B_C_current  | Feature  |  Discrete  |  |
|  correlation_phase_A_B_current  | Feature  |  Discrete  |  |
|  correlation_phase_A_C_current  | Feature  |  Discrete  |  |
|  correlation_phase_B_C_current  | Feature  |  Discrete  |  |
|  max_phase_A_current  | Feature  |  Discrete  |  |
|  max_phase_B_current  | Feature  |  Discrete  |  |
|  max_phase_C_current  | Feature  |  Discrete  |  |
|  min_phase_A_current  | Feature  |  Discrete  |  |
|  min_phase_B_current  | Feature  |  Discrete  |  |
|  min_phase_C_current  | Feature  |  Discrete  |  |
|  energy_phase_A_voltage  | Feature  |  Discrete  |  |
|  energy_phase_B_voltage  | Feature  |  Discrete  |  |
|  energy_phase_C_voltage  | Feature  |  Discrete  |  |
|  distance_phase_A_voltage  | Feature  |  Discrete  |  |
|  distance_phase_B_voltage  | Feature  |  Discrete  |  |
|  distance_phase_C_voltage  | Feature  |  Discrete  |  |
|  rms_phase_A_voltage  | Feature  |  Discrete  |  |
|  rms_phase_B_voltage  | Feature  |  Discrete  |  |
|  rms_phase_C_voltage  | Feature  |  Discrete  |  |
|  kurtosis_phase_A_voltage  | Feature  |  Discrete  |  |
|  kurtosis_phase_B_voltage  | Feature  |  Discrete  |  |
|  kurtosis_phase_C_voltage  | Feature  |  Discrete  |  |
|  skewness_phase_A_voltage  | Feature  |  Discrete  |  |
|  skewness_phase_B_voltage  | Feature  |  Discrete  |  |
|  skewness_phase_C_voltage  | Feature  |  Discrete  |  |
|  maxFrequency_phase_A_voltage  | Feature  |  Discrete  |  |
|  maxFrequency_phase_B_voltage  | Feature  |  Discrete  |  |
|  maxFrequency_phase_C_voltage  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_A_voltage  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_B_voltage  | Feature  |  Discrete  |  |
|  powerBandwidth_phase_C_voltage  | Feature  |  Discrete  |  |
|  auc_phase_A_voltage  | Feature  |  Discrete  |  |
|  auc_phase_B_voltage  | Feature  |  Discrete  |  |
|  auc_phase_C_voltage  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_A_voltage  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_B_voltage  | Feature  |  Discrete  |  |
|  pk_pk_distance_phase_C_voltage  | Feature  |  Discrete  |  |
|  slope_phase_A_voltage  | Feature  |  Discrete  |  |
|  slope_phase_B_voltage  | Feature  |  Discrete  |  |
|  slope_phase_C_voltage  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_A_voltage  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_B_voltage  | Feature  |  Discrete  |  |
|  shannon_entropy_phase_C_voltage  | Feature  |  Discrete  |  |
|  mean_phase_A_voltage  | Feature  |  Discrete  |  |
|  mean_phase_B_voltage  | Feature  |  Discrete  |  |
|  mean_phase_C_voltage  | Feature  |  Discrete  |  |
|  geometric_mean_phase_A_voltage  | Feature  |  Discrete  |  |
|  geometric_mean_phase_B_voltage  | Feature  |  Discrete  |  |
|  geometric_mean_phase_C_voltage  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_A_voltage  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_B_voltage  | Feature  |  Discrete  |  |
|  harmonic_mean_phase_C_voltage  | Feature  |  Discrete  |  |
|  variance_phase_A_voltage  | Feature  |  Discrete  |  |
|  variance_phase_B_voltage  | Feature  |  Discrete  |  |
|  variance_phase_C_voltage  | Feature  |  Discrete  |  |
|  stdev_phase_A_voltage  | Feature  |  Discrete  |  |
|  stdev_phase_B_voltage  | Feature  |  Discrete  |  |
|  stdev_phase_C_voltage  | Feature  |  Discrete  |  |
|  median_phase_A_voltage  | Feature  |  Discrete  |  |
|  median_phase_B_voltage  | Feature  |  Discrete  |  |
|  median_phase_C_voltage  | Feature  |  Discrete  |  |
|  covariance_phase_A_B_voltage  | Feature  |  Discrete  |  |
|  covariance_phase_A_C_voltage  | Feature  |  Discrete  |  |
|  covariance_phase_B_C_voltage  | Feature  |  Discrete  |  |
|  correlation_phase_A_B_voltage  | Feature  |  Discrete  |  |
|  correlation_phase_A_C_voltage  | Feature  |  Discrete  |  |
|  correlation_phase_B_C_voltage  | Feature  |  Discrete  |  |
|  max_phase_A_voltage  | Feature  |  Discrete  |  |
|  max_phase_B_voltage  | Feature  |  Discrete  |  |
|  max_phase_C_voltage  | Feature  |  Discrete  |  |
|  min_phase_A_voltage  | Feature  |  Discrete  |  |
|  min_phase_B_voltage  | Feature  |  Discrete  |  |
|  min_phase_C_voltage  | Feature  |  Discrete  |  |

The FADbF dataset companion the paper entitled "Fault Distance Estimation for Transmission Lines with Dynamic Regressor Selection", published in Journal_XXX, vol. XX, no. XX, pp. XX–XX, year 202X, doi: XXXXXXXXX. More information about the dataset can be found in this reference.
