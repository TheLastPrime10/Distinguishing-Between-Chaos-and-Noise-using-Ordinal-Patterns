EEG Time Series Analysis using Ordinal Pattern Methods

This repository contains Python code developed as part of my Data Science Minor Project at IISER Thiruvananthapuram.

Project Overview

The project investigates whether ordinal pattern-based complexity measures can distinguish deterministic dynamics from stochastic noise in time-series data. This implementation applies these techniques to 16-channel EEG recordings, extracting complexity measures from each channel independently.

The analysis is based on ordinal pattern statistics, which are robust to monotonic transformations and provide a useful framework for characterizing nonlinear dynamical systems.

Methods

The code implements:

* Ordinal Pattern (Permutation) Analysis
* Permutation Entropy
* Statistical Complexity
* Missing Ordinal Pattern Analysis
* Complexity–Entropy Plane visualization

The extracted measures can be used to compare the dynamical characteristics of EEG signals across different channels.

Dataset

The code is designed for 16-channel EEG recordings. Users may replace the input data with their own EEG recordings of the same format.
