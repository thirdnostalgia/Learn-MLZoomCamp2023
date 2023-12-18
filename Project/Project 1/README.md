# This is the first project to complete ML Zoomcamp 2023

## Proble Statements & Goals

This project goal is to make a prediction for diamonds price based on certain features (Carats, Size, Clarity, Color, Cut, deptth) and to know which feature have the biggest relation with the diamonds's price.

## Methodology

- For this project I used MSE for the metric
- I train the model with KNN, Random Forest , Adaboost algorithm

## Features
- Price : Our target, USD currency
- Carat : Presented weight from the diamonds(0.2 - 5.01)
- Cut : The quality for the diamonds cutting (Fair, Good, Very ood, Premium and Ideal)
- Color : J (The Worst) to D (Tje Best)
- Clarity : I1 (The Worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (The Best)
- x: length of diamonds in mm (0-10.74).
- y: width of diamonds in mm (0-58.9).
- z: depth of diamonds in mm (0-31.8).
- depth:  z/mean(x, y) = 2 * z/(x + y) (43-79).
- table: width of top side (43-95).