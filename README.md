# STS_NanoSurf_Deriv_Smooth_Interp
 Derivate, Smooth, and Interpolate i-v Curves from STS NanoSurf

This Python script uses pandas, numpy, matplotlib, scipy, and ipywidgets to smooth the derivative of data from CSV files. It provides an interactive interface with sliders for smoothing and interpolation, allowing users to explore and export the smoothed derivative.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scipy
- ipywidgets

## How to Use

1. Ensure you have Python installed in your environment.
2. Install the required libraries by running the following command:

    ```bash
    pip install pandas numpy matplotlib scipy ipywidgets
    ```

3. Run the Python script. It will display an interactive interface with dropdowns and sliders.
4. Select a CSV file, adjust the smoothing and interpolation parameters using sliders, and provide an export filename.
5. Click the "Salvar Dados" (Save Data) button to export the processed data to a text file.

## Script Overview

- The script loads CSV data, calculates the derivative, smoothes the derivative using convolution, and interpolates the smoothed data using a polynomial.
- The smoothed and interpolated derivatives are then plotted, and users can export the processed data.
