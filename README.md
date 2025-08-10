Spatial Interpolation of Rainfall using Kriging vs Machine Learning (Synthetic Data)

Author: Amos Meremu Dogiye
GitHub: https://github.com/GTVSOFT

    Synthetic rainfall data generation (>100 random points).

    Kriging interpolation directly in GEE.

    Random Forest regression for spatial prediction.

    Visual comparison of Kriging vs ML results.

    Difference map to highlight variations between methods.

    Easy export of synthetic dataset (provided as Excel file).

Dataset

A sample synthetic rainfall dataset generated from this script is included:
📄 synthetic_rainfall_points.xlsx
Columns:

    id — Unique point ID.

    longitude, latitude — Coordinates in decimal degrees.

    rainfall — Simulated rainfall measurement (mm).

Requirements

    A Google Earth Engine account (Sign up here).

    Access to the GEE Code Editor (https://code.earthengine.google.com/).

Usage

    Open the GEE Code Editor.

    Paste the JavaScript code from Spatial-Interpolation-of-Rainfall-using-Kriging-vs-ML.js.

    Adjust parameters as needed:

        NUM_POINTS → number of rainfall stations to simulate.

        RANDOM_SEED → reproducibility.

        EXPORT_SCALE → spatial resolution for ML training/prediction.

    Run the script to:

        View synthetic rainfall points.

        See Kriging and ML interpolation results.

        Compare both methods visually.

    Optionally export results for further analysis.

Output

    Layers in GEE Map:

        Rainfall point locations.

        Kriging interpolated surface.

        Random Forest predicted surface.

        Difference map (Kriging – RF).

    Synthetic dataset (Excel) for reproducibility and testing.

Customization

    Change AOI coordinates to target different regions.

    Adjust rainfall generation formula for different spatial patterns.

    Replace synthetic data with real rainfall station measurements.

License

This project is provided for educational and research purposes only.
