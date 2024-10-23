# LoDCalculator

Overview

LoDCalculator is a Blender add-on designed to analyze the level of detail (LoD) of 3D models. It evaluates geometric and radiometric fidelity, providing scores and raw data that help assess the quality of your models.
Installation

Download the LoDCalculator.py file from this repository.
Open Blender and navigate to the Preferences menu.
Go to the Add-ons section.
Click on Install from local disk and select the downloaded .py file.
The add-on is now installed and a new section called LoDCalculator will appear in the Scene Properties panel.

Usage

Select a 3D Model: Choose the model you want to analyze in the Blender viewport.
Analyze the Model: Click the Calculate Result button in the LoDCalculator panel.
Review Results: The results will display the LoD score and analysis data. If there are issues (e.g., no model selected, non-mesh object, or model without textures), an error notification will appear, and the analysis will receive the lowest possible score.

Scoring System

LoD Score: Ranges from 1 to 5, with half-point divisions, evaluating the overall model quality.
Partial Scores:
    Geometric Fidelity: Ranges from 1 to 3, assessing the geometric detail of the model.
    Radiometric Fidelity: Ranges from 1 to 3, evaluating textures and materials.

Analysis Data

When an analysis is executed, you can view:

Raw Data: Including the last interquartile range and average angles of the model's faces.
Model Statistics: Number of faces and meshes, average faces per mesh, number of textures and materials, average resolution of textures, and percentage of tiled faces.

Relative Data Comparison

LoDCalculator can compare models of different scales, whether they consist of a single mesh or multiple complex meshes.
Examples

Usage examples with their corresponding scores will be provided to illustrate the capabilities of LoDCalculator.
Uninstallation

To uninstall LoDCalculator:

Go back to Blender's Preferences.
Navigate to the Add-ons section.
Click on Uninstall for LoDCalculator.

Contributing

If you would like to contribute to LoDCalculator, feel free to fork the repository and submit a pull request.
License

This project is licensed under the MIT License - see the LICENSE file for details.
