# SAM_predict
A convolutional neural network for predicting the Southern Annular Mode, with some explainable artifical intelligence (XAI) features.

The model is constructed to predict deviations of the Southern Annular Mode (aka Antarctic Oscillation, see https://en.wikipedia.org/wiki/Antarctic_oscillation) from the climatological mean. The predictor is mean sea level pressure (MSLP), realized on a quarter-degree grid of the southern hemisphere. Data is from the ERA5 reanalysis dataset (https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5).

Custom, gradient-based XAI functions are included under the "XAI" heading in the notebook. Also included are some visualization tools built using Cartopy.
