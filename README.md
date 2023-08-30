# Time-Series-Metrics

## Custom Evaluation Metrics

This repository includes a collection of custom evaluation metrics that can be useful for assessing the performance of predictive models. These metrics cover various aspects of prediction accuracy, error, and directional accuracy.

### Metrics List
1. Mean Squared Error (MSE): Measures the average squared difference between predictions and actual values.
2. Root Mean Squared Error (RMSE): RMSE is the square root of the MSE, providing a measure of the average magnitude of errors.
3. Normalized RMSE (NRMSE): RMSE scaled by the range of the true values, providing a relative error measure.
4. Mean Error (ME): Measures the average of errors (residuals).
5. Mean Absolute Error (MAE): Computes the average absolute differences between predictions and actual values.
Median Absolute Deviation (MAD): Measures the median absolute difference between predictions and actual values.
Geometric Mean Absolute Error (GMAE): GMAE is a geometric mean of the absolute errors.
Median Absolute Deviation of Errors (MdAE): Measures the median absolute difference of errors.
Mean Percentage Error (MPE): Computes the average percentage difference between predictions and actual values.
Mean Absolute Percentage Error (MAPE): Calculates the average absolute percentage difference.
Median Absolute Percentage Error (MdAPE): Measures the median absolute percentage difference.
Symmetric Mean Absolute Percentage Error (SMAPE): Provides a symmetric percentage difference measure.
Symmetric Median Absolute Percentage Error (SMDAPE): A symmetric version of MdAPE.
Mean Arctangent Absolute Percentage Error (MAAPE): Utilizes the arctangent function for better stability.
Mean Absolute Scaled Error (MASE): Scales the MAE by the mean absolute error of a naive forecast.
Standardized Absolute Error (std_AE): Standardizes the absolute errors.
Standardized Absolute Percentage Error (std_APE): Standardizes the absolute percentage errors.
Root Mean Squared Percentage Error (RMSPE): Computes the RMS of percentage differences.
Root Median Squared Percentage Error (RMDSPE): Similar to RMSPE but uses the median.
Root Mean Squared Scaled Error (RMSSE): Scales the RMSE by the mean absolute error of a naive forecast.
Integrated Normalized Root Squared Error (INRSE): An integrated version of the NRMSE.
Relative Root Squared Error (RRSE): Measures the relative RMSE.
Mean Relative Error (MRE): Computes the average relative difference.
Relative Absolute Error (RAE): Measures the relative absolute differences.
Mean Relative Absolute Error (MRAE): Calculates the average of RAE.
Median Relative Absolute Error (MdRAE): Measures the median of RAE.
Geometric Mean Relative Absolute Error (GMRAE): Similar to GMAE but for relative errors.
Mean Bounded Relative Absolute Error (MBRAE): A bounded version of MRAE.
Unscaled Mean Bounded Relative Absolute Error (UMBRAE): Unscaled version of MBRAE.
Mean Directional Accuracy (MDA): Measures the proportion of correct directional predictions.
