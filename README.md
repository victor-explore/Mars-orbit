This project implements an algorithm to analyze and optimize Mars' orbit parameters based on opposition data.

## Overview

The algorithm uses a model of Mars' orbit to find the best parameters that minimize the angular error between predicted and observed oppositions. It employs an iterative optimization approach to search through different combinations of orbital parameters.

## Key Features

- Implementation of Mars' orbit model with equant
- Optimization of orbital parameters (c, r, e1, e2, z, s)
- Calculation of angular errors for each opposition
- Minimization of maximum angular error

## Data

The project uses the `01_data_mars_opposition_updated.csv` file, which contains:
- Dates of Mars oppositions
- Mars' heliocentric longitude in the ecliptic coordinate system
- Mars' geocentric latitudinal position

## Main Functions

1. `MarsEquantModel(c, r, e1, e2, z, s, times, oppositions)`
2. `bestOrbitInnerParams(r, s, times, oppositions)`
3. `bestS(r, times, oppositions)`
4. `bestR(s, times, oppositions)`
5. `bestMarsOrbitParams(times, oppositions)`

## Usage

To run the Mars orbit analysis:

1. Ensure you have Python 3.9.12 installed.
2. Place the `01_data_mars_opposition_updated.csv` file in the same directory as the script.
3. Run the `Assignment2.py` script.

## Results

The algorithm outputs:
- Optimized orbital parameters (c, r, e1, e2, z, s)
- Angular errors for each opposition
- Maximum angular error

## Visualization

The project includes plot(s) to visualize the results. These can be found in the `PlotY.png` files, where Y is the plot number.

## Report

A detailed report of the implementation and results can be found in the `Report2.pdf` file.


