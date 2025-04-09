% This is a repository of the Matlab code used to create, train and evaluate a neural network to model LIBS data.
% ML_Regression_LIBS_AIR_FUEL.m is the main file which performs the task
% LIBS_JB_Calibration_20240115.mat contains the dataset used for modelling
% CH_polyModel.mat and Z_polyModel.mat contain the fit functions for the variables CH4 and Z, which were obtained by using 2D polynomial fits on the dataset.
% Both methods (2D polynomials and NN) are used, since the objective is to evaluate not only the accuracy but also the robustness of the NN model.
%
% To run, simply open ML_Regression_LIBS_AIR_FUEL.m in Matlab with the remaining files in the same directory.
