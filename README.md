# Image Composite Prototype

This folder contains a prototype for blending images using OpenCV. Using the Hday2night.zip samples

## Files in this directory
- **analyze_composite.ipynb**: The notebook used to run the analysis.
- **real.jpg**: The original target background photo.
- **composite.jpg**: The image to blend into the background.
- **mask.png**: The mask defining the area to blend.
- **prototype_result.png**: The final output image.

## How to run
1. Make sure you have Python and Jupyter installed.
2. Open nalyze_composite.ipynb in your Jupyter environment.
3. Run the cells in the notebook sequentially to perform the image compositing and analysis.

## Expected Output
The script generates a composite image and calculates the consistency metrics  to compare how well the composite fits into the real background.
