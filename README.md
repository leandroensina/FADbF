# Fault Analysis Database with Features (FADbF)

The FADbF dataset companions the paper entitled "Fault Distance Estimation for Transmission Lines with Dynamic Regressor Selection", published in Neural Computing and Applications, vol. XX, no. XX, pp. XX–XX, year 202X, doi: XXXXXXXXX. More information about the dataset can be found in this reference.

**Associated Tasks**: classification and regression

**Instances**: 168,000

**Attributes**: 128, including the two possible targets

**Additional Information**: this database comprises several attributes extracted from time series of fault simulations of a transmission line with 500 kV, 414 km, and 60 Hz. In total, we extracted 21 features separately for each of the three phases for both voltage and current waveforms along two post-fault cycles from a single terminal, resulting in 126 attributes (21 * 3 * 2 = 126) in addition to the two possible targets, i.e., fault type (classification task) and fault location (regression task). If desired, the fault type can also be used as a feature for the fault location task.

**Attribute list**:
|  Feature name  |  Role |  Type  |  Description  |
|  ------------  |  ---- |  ----  |  -----------  |
|  fault_type  | Target  |  Categorical  | AG, BG, CG, AB, AC, BC, ABG, ACG, BCG, ABC |
|  fault_location  | Target  |  Discrete  | Values varying from 4.14 km to 414 km, representing the position where the fault occurred in the transmission line |
|  energy_phase_A_current  | Feature  |  Discrete  | Absolute energy, phase A for the current signal |
|  energy_phase_B_current  | Feature  |  Discrete  | Absolute energy, phase B for the current signal |
|  energy_phase_C_current  | Feature  |  Discrete  | Absolute energy, phase C for the current signal |
|  distance_phase_A_current  | Feature  |  Discrete  | Signal traveled distance, phase A for the current signal |
|  distance_phase_B_current  | Feature  |  Discrete  | Signal traveled distance, phase B for the current signal |
|  distance_phase_C_current  | Feature  |  Discrete  | Signal traveled distance, phase C for the current signal |
|  rms_phase_A_current  | Feature  |  Discrete  | Root mean square, phase A for the current signal |
|  rms_phase_B_current  | Feature  |  Discrete  | Root mean square, phase B for the current signal |
|  rms_phase_C_current  | Feature  |  Discrete  | Root mean square, phase C for the current signal |
|  kurtosis_phase_A_current  | Feature  |  Discrete  | Kurtosis, phase A for the current signal |
|  kurtosis_phase_B_current  | Feature  |  Discrete  | Kurtosis, phase B for the current signal |
|  kurtosis_phase_C_current  | Feature  |  Discrete  | Kurtosis, phase C for the current signal |
|  skewness_phase_A_current  | Feature  |  Discrete  | Skewness, phase A for the current signal |
|  skewness_phase_B_current  | Feature  |  Discrete  | Skewness, phase B for the current signal |
|  skewness_phase_C_current  | Feature  |  Discrete  | Skewness, phase C for the current signal |
|  maxFrequency_phase_A_current  | Feature  |  Discrete  | Maximum frequency, phase A for the current signal |
|  maxFrequency_phase_B_current  | Feature  |  Discrete  | Maximum frequency, phase B for the current signal |
|  maxFrequency_phase_C_current  | Feature  |  Discrete  | Maximum frequency, phase C for the current signal |
|  powerBandwidth_phase_A_current  | Feature  |  Discrete  | Power spectrum density bandwidth, phase A for the current signal |
|  powerBandwidth_phase_B_current  | Feature  |  Discrete  | Power spectrum density bandwidth, phase B for the current signal |
|  powerBandwidth_phase_C_current  | Feature  |  Discrete  | Power spectrum density bandwidth, phase C for the current signal |
|  auc_phase_A_current  | Feature  |  Discrete  | Area under the curve, phase A for the current signal |
|  auc_phase_B_current  | Feature  |  Discrete  | Area under the curve, phase B for the current signal |
|  auc_phase_C_current  | Feature  |  Discrete  | Area under the curve, phase C for the current signal |
|  pk_pk_distance_phase_A_current  | Feature  |  Discrete  | Peak to peak distance, phase A for the current signal |
|  pk_pk_distance_phase_B_current  | Feature  |  Discrete  | Peak to peak distance, phase B for the current signal |
|  pk_pk_distance_phase_C_current  | Feature  |  Discrete  | Peak to peak distance, phase C for the current signal |
|  slope_phase_A_current  | Feature  |  Discrete  | Slope, phase A for the current signal |
|  slope_phase_B_current  | Feature  |  Discrete  | Slope, phase B for the current signal |
|  slope_phase_C_current  | Feature  |  Discrete  | Slope, phase C for the current signal |
|  shannon_entropy_phase_A_current  | Feature  |  Discrete  | Shannon Entropy, phase A for the current signal |
|  shannon_entropy_phase_B_current  | Feature  |  Discrete  | Shannon Entropy, phase B for the current signal |
|  shannon_entropy_phase_C_current  | Feature  |  Discrete  | Shannon Entropy, phase C for the current signal |
|  mean_phase_A_current  | Feature  |  Discrete  | Arithmetic mean, phase A for the current signal |
|  mean_phase_B_current  | Feature  |  Discrete  | Arithmetic mean, phase B for the current signal |
|  mean_phase_C_current  | Feature  |  Discrete  | Arithmetic mean, phase C for the current signal |
|  geometric_mean_phase_A_current  | Feature  |  Discrete  | Geometric mean, phase A for the current signal |
|  geometric_mean_phase_B_current  | Feature  |  Discrete  | Geometric mean, phase B for the current signal |
|  geometric_mean_phase_C_current  | Feature  |  Discrete  | Geometric mean, phase C for the current signal |
|  harmonic_mean_phase_A_current  | Feature  |  Discrete  | Harmonic mean, phase A for the current signal |
|  harmonic_mean_phase_B_current  | Feature  |  Discrete  | Harmonic mean, phase B for the current signal |
|  harmonic_mean_phase_C_current  | Feature  |  Discrete  | Harmonic mean, phase C for the current signal |
|  variance_phase_A_current  | Feature  |  Discrete  | Variance, phase A for the current signal |
|  variance_phase_B_current  | Feature  |  Discrete  | Variance, phase B for the current signal |
|  variance_phase_C_current  | Feature  |  Discrete  | Variance, phase C for the current signal |
|  stdev_phase_A_current  | Feature  |  Discrete  | Standard deviation, phase A for the current signal |
|  stdev_phase_B_current  | Feature  |  Discrete  | Standard deviation, phase B for the current signal |
|  stdev_phase_C_current  | Feature  |  Discrete  | Standard deviation, phase C for the current signal |
|  median_phase_A_current  | Feature  |  Discrete  | Median, phase A for the current signal |
|  median_phase_B_current  | Feature  |  Discrete  | Median, phase B for the current signal |
|  median_phase_C_current  | Feature  |  Discrete  | Median, phase C for the current signal |
|  covariance_phase_A_B_current  | Feature  |  Discrete  | Covariance of phases A and B, current signal |
|  covariance_phase_A_C_current  | Feature  |  Discrete  | Covariance of phases A and C, current signal |
|  covariance_phase_B_C_current  | Feature  |  Discrete  | Covariance of phases B and C, current signal |
|  correlation_phase_A_B_current  | Feature  |  Discrete  | Pearson’s correlation of phases A and B, current signal |
|  correlation_phase_A_C_current  | Feature  |  Discrete  | Pearson’s correlation of phases A and C, current signal |
|  correlation_phase_B_C_current  | Feature  |  Discrete  | Pearson’s correlation of phases B and C, current signal |
|  max_phase_A_current  | Feature  |  Discrete  | Maximum value, phase A for the current signal |
|  max_phase_B_current  | Feature  |  Discrete  | Maximum value, phase B for the current signal |
|  max_phase_C_current  | Feature  |  Discrete  | Maximum value, phase C for the current signal |
|  min_phase_A_current  | Feature  |  Discrete  | Minimum value, phase A for the current signal |
|  min_phase_B_current  | Feature  |  Discrete  | Minimum value, phase B for the current signal |
|  min_phase_C_current  | Feature  |  Discrete  | Minimum value, phase C for the current signal |
|  energy_phase_A_voltage  | Feature  |  Discrete  | Absolute energy, phase A for the voltage signal |
|  energy_phase_B_voltage  | Feature  |  Discrete  | Absolute energy, phase B for the voltage signal |
|  energy_phase_C_voltage  | Feature  |  Discrete  | Absolute energy, phase C for the voltage signal |
|  distance_phase_A_voltage  | Feature  |  Discrete  | Signal traveled distance, phase A for the voltage signal |
|  distance_phase_B_voltage  | Feature  |  Discrete  | Signal traveled distance, phase B for the voltage signal |
|  distance_phase_C_voltage  | Feature  |  Discrete  | Signal traveled distance, phase C for the voltage signal |
|  rms_phase_A_voltage  | Feature  |  Discrete  | Root mean square, phase A for the voltage signal |
|  rms_phase_B_voltage  | Feature  |  Discrete  | Root mean square, phase B for the voltage signal |
|  rms_phase_C_voltage  | Feature  |  Discrete  | Root mean square, phase C for the voltage signal |
|  kurtosis_phase_A_voltage  | Feature  |  Discrete  | Kurtosis, phase A for the voltage signal |
|  kurtosis_phase_B_voltage  | Feature  |  Discrete  | Kurtosis, phase B for the voltage signal |
|  kurtosis_phase_C_voltage  | Feature  |  Discrete  | Kurtosis, phase C for the voltage signal |
|  skewness_phase_A_voltage  | Feature  |  Discrete  | Skewness, phase A for the voltage signal |
|  skewness_phase_B_voltage  | Feature  |  Discrete  | Skewness, phase B for the voltage signal |
|  skewness_phase_C_voltage  | Feature  |  Discrete  | Skewness, phase C for the voltage signal |
|  maxFrequency_phase_A_voltage  | Feature  |  Discrete  | Maximum frequency, phase A for the voltage signal |
|  maxFrequency_phase_B_voltage  | Feature  |  Discrete  | Maximum frequency, phase B for the voltage signal |
|  maxFrequency_phase_C_voltage  | Feature  |  Discrete  | Maximum frequency, phase C for the voltage signal |
|  powerBandwidth_phase_A_voltage  | Feature  |  Discrete  | Power spectrum density bandwidth, phase A for the voltage signal |
|  powerBandwidth_phase_B_voltage  | Feature  |  Discrete  | Power spectrum density bandwidth, phase B for the voltage signal |
|  powerBandwidth_phase_C_voltage  | Feature  |  Discrete  | Power spectrum density bandwidth, phase C for the voltage signal |
|  auc_phase_A_voltage  | Feature  |  Discrete  | Area under the curve, phase A for the voltage signal |
|  auc_phase_B_voltage  | Feature  |  Discrete  | Area under the curve, phase B for the voltage signal |
|  auc_phase_C_voltage  | Feature  |  Discrete  | Area under the curve, phase C for the voltage signal |
|  pk_pk_distance_phase_A_voltage  | Feature  |  Discrete  | Peak to peak distance, phase A for the voltage signal |
|  pk_pk_distance_phase_B_voltage  | Feature  |  Discrete  | Peak to peak distance, phase B for the voltage signal |
|  pk_pk_distance_phase_C_voltage  | Feature  |  Discrete  | Peak to peak distance, phase C for the voltage signal |
|  slope_phase_A_voltage  | Feature  |  Discrete  | Slope, phase A for the voltage signal |
|  slope_phase_B_voltage  | Feature  |  Discrete  | Slope, phase B for the voltage signal |
|  slope_phase_C_voltage  | Feature  |  Discrete  | Slope, phase C for the voltage signal |
|  shannon_entropy_phase_A_voltage  | Feature  |  Discrete  | Shannon Entropy, phase A for the voltage signal |
|  shannon_entropy_phase_B_voltage  | Feature  |  Discrete  | Shannon Entropy, phase B for the voltage signal |
|  shannon_entropy_phase_C_voltage  | Feature  |  Discrete  | Shannon Entropy, phase C for the voltage signal |
|  mean_phase_A_voltage  | Feature  |  Discrete  | Arithmetic mean, phase A for the voltage signal |
|  mean_phase_B_voltage  | Feature  |  Discrete  | Arithmetic mean, phase B for the voltage signal |
|  mean_phase_C_voltage  | Feature  |  Discrete  | Arithmetic mean, phase C for the voltage signal |
|  geometric_mean_phase_A_voltage  | Feature  |  Discrete  | Geometric mean, phase A for the voltage signal |
|  geometric_mean_phase_B_voltage  | Feature  |  Discrete  | Geometric mean, phase B for the voltage signal |
|  geometric_mean_phase_C_voltage  | Feature  |  Discrete  | Geometric mean, phase C for the voltage signal |
|  harmonic_mean_phase_A_voltage  | Feature  |  Discrete  | Harmonic mean, phase A for the voltage signal |
|  harmonic_mean_phase_B_voltage  | Feature  |  Discrete  | Harmonic mean, phase B for the voltage signal |
|  harmonic_mean_phase_C_voltage  | Feature  |  Discrete  | Harmonic mean, phase C for the voltage signal |
|  variance_phase_A_voltage  | Feature  |  Discrete  | Variance, phase A for the voltage signal |
|  variance_phase_B_voltage  | Feature  |  Discrete  | Variance, phase B for the voltage signal |
|  variance_phase_C_voltage  | Feature  |  Discrete  | Variance, phase C for the voltage signal |
|  stdev_phase_A_voltage  | Feature  |  Discrete  | Standard deviation, phase A for the voltage signal |
|  stdev_phase_B_voltage  | Feature  |  Discrete  | Standard deviation, phase B for the voltage signal |
|  stdev_phase_C_voltage  | Feature  |  Discrete  | Standard deviation, phase C for the voltage signal |
|  median_phase_A_voltage  | Feature  |  Discrete  | Median, phase A for the voltage signal |
|  median_phase_B_voltage  | Feature  |  Discrete  | Median, phase B for the voltage signal |
|  median_phase_C_voltage  | Feature  |  Discrete  | Median, phase C for the voltage signal |
|  covariance_phase_A_B_voltage  | Feature  |  Discrete  | Covariance of phases A and B, voltage signal |
|  covariance_phase_A_C_voltage  | Feature  |  Discrete  | Covariance of phases A and C, voltage signal |
|  covariance_phase_B_C_voltage  | Feature  |  Discrete  | Covariance of phases B and C, voltage signal |
|  correlation_phase_A_B_voltage  | Feature  |  Discrete  | Pearson’s correlation of phases A and B, voltage signal |
|  correlation_phase_A_C_voltage  | Feature  |  Discrete  | Pearson’s correlation of phases A and C, voltage signal |
|  correlation_phase_B_C_voltage  | Feature  |  Discrete  | Pearson’s correlation of phases B and C, voltage signal |
|  max_phase_A_voltage  | Feature  |  Discrete  | Maximum value, phase A for the voltage signal |
|  max_phase_B_voltage  | Feature  |  Discrete  | Maximum value, phase B for the voltage signal |
|  max_phase_C_voltage  | Feature  |  Discrete  | Maximum value, phase C for the voltage signal |
|  min_phase_A_voltage  | Feature  |  Discrete  | Minimum value, phase A for the voltage signal |
|  min_phase_B_voltage  | Feature  |  Discrete  | Minimum value, phase B for the voltage signal |
|  min_phase_C_voltage  | Feature  |  Discrete  | Minimum value, phase C for the voltage signal |
