Logo Feature Extractor

A Python tool that automatically extracts key visual design features from brand logos, including dimensional properties, color composition, and design principles compliance.

🎯 Project Overview

This project analyzes brand logos to extract quantitative design features that can be used for design analysis, brand studies, or machine learning applications. The tool processes logo images and calculates various visual metrics including geometric properties, color distribution, and adherence to design principles.

🔍 Features Extracted

The system extracts the following key features from logo images:

1)Dimensional Features

-Logo Height: Pixel height of the logo
-Logo Width: Pixel width of the logo
-Aspect Ratio: Width to height ratio

2)Design Principle Metrics

-Golden Ratio Conformance Score: Measures how closely the logo's proportions align with the golden ratio (1.618)
-Percent Negative Space: Percentage of empty/background space in the logo design

3)Color Analysis

-Percent Warm Colors: Percentage of warm colors (reds, oranges, yellows) in the logo
-Percent Cool Colors: Percentage of cool colors (blues, greens, purples) in the logo
-Percent Neutral Colors: Percentage of neutral colors (whites, grays, blacks, browns) in the logo

📊 Dataset
The project includes:

-10 logo images in various formats (PNG/JPG)
-Extracted features dataset with all calculated metrics
-Logo attributes file containing the complete feature matrix

🔧 Technologies Used

-Python 3.8+
-Computer Vision: OpenCV, PIL (Pillow)
-Data Processing: pandas, numpy
-Color Analysis: Custom color classification algorithms
-Mathematical Calculations: scipy for geometric computations

🔍 Feature Descriptions
1)Golden Ratio Conformance Score

Range: 0.0 to 1.0
Description: Measures how closely the logo's proportions match the golden ratio
1.0: Perfect golden ratio compliance
0.0: No golden ratio relationship

2)Negative Space Percentage

Range: 0% to 100%
Description: Amount of empty or background space in the logo
Higher values: More minimalist, cleaner designs
Lower values: More detailed, complex designs

3)Color Percentages

Warm Colors: Reds, oranges, yellows, warm pinks
Cool Colors: Blues, greens, purples, cool grays
Neutral Colors: Black, white, grays, browns, beiges
Total: Always sums to 100%

🔮 Future Enhancements

 -Add symmetry analysis
 -Include typography feature extraction
 -Implement edge complexity metrics
 -Add brand recognition confidence scores
 -Support for vector format logos (SVG)
