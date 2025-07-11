# Wrist Angle 
This project uses the DeepLabCut GUI to label and predict joint positions in videos, then analyzes the output CSV file with a Jupyter Notebook (`angle.ipynb`).

## 📌 Project Overview

1. **Label and train using DeepLabCut GUI**
   - Load the project `Wrist_angle_DLC`.
   - Analyze new videos using `shuffle 11` (the best performing model so far).
   - Export the results as CSV files.

2. **Analyze in Jupyter Notebook**
   - Load the exported CSV file.
   - Adjust parameters (`distance`, `window`, and `remove_peaks`) to better segment each stimulation.
   - Visualize the results with plots.

## 📊 Results

![Wrist angle over time](figures/0130_1.png)
![Single peak plot](figures/0130_2.png)
![Exponential Fit](figures/0130_3.png)
