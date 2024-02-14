# Large-scale Wave Energy Farm

[maple_drift_1a4b.csv](maple_drift_1a4b.csv) contains 50,000 rows for data cleaning and machine learning practice. The target column is `Total_Power`.

Source [Neshat, Alexander, Sergiienko and Wagner (2020), UCI Machine Learning Repository](https://doi.org/10.24432/C5GG7Q). License [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

The sample contains 49,550 source rows. Sampling seed 308998151. Perth and Sydney layouts with 49 converters were sampled in proportion to their source counts.

Removed the 49 individual power columns (Power1 through Power49) and qW. The individual power columns and q-factor are simulation outputs. Their removal leaves converter coordinates and scenario as model inputs.

Added 450 duplicate rows, empty cells, missing-value markers, decimal commas and out-of-range values. Added irregular case and whitespace to a categorical column.
