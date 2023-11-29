# Marching Squares Algorithm with OpenCV

This Python project utilizes mathematical functions to create data and applies the marching squares algorithm to determine contours. The visual results are rendered with OpenCV.

## Key Features:

- Utilization of the marching squares algorithm to detect contours in a data grid.
- Experimentation with various mathematical functions to generate diverse patterns.
- Use of the PIL library for image creation and OpenCV for drawing contours.
- Easy execution on Google Colab or locally.

## Included Examples of Mathematical Functions:

- \( F(x, y) = \sin(x) \cdot \cos(y) \) for periodic variation.

    ![Screenshot 2023-11-29 202456](https://github.com/laidouniyoussef/MarchingSquare/assets/64043301/2f758fa2-1d2a-43fb-8c16-f46158dd1433)

- \( F(x, y) = e^{-\frac{x^2 + y^2}{1000.0}} \) for Gaussian decay.

![fct](https://github.com/laidouniyoussef/MarchingSquare/assets/64043301/66e876f5-e0aa-4b03-be86-5c1f9fa00101)

- \( F(x, y) = \sqrt{x^2 + y^2} \) for radial gradient.

    ![Screenshot 2023-11-29 202606](https://github.com/laidouniyoussef/MarchingSquare/assets/64043301/531c4454-ca67-467d-81ab-6ac7d8c809b6)

- \( F(x, y) = \cos(\sqrt{x^2 + y^2}) \) for cosine rings.

     ![Screenshot 2023-11-29 202553](https://github.com/laidouniyoussef/MarchingSquare/assets/64043301/44c516f0-5eab-4f2a-8873-d5b11189ffd1)

- \( F(x, y) = x^2 + y^2 - 500 \) for a polynomial function.

    ![Screenshot 2023-11-29 202536](https://github.com/laidouniyoussef/MarchingSquare/assets/64043301/7851d9fb-a449-481b-9270-55a8c5e410a8)



## How to Use:

1. Run the code on Google Colab or locally.
2. Experiment with different mathematical functions and thresholds to obtain unique results.
3. Visualize the generated patterns directly with OpenCV.
