
![image](https://github.com/TuncerCemUgurluer/Thorax_CT_Denoising/assets/159438469/84ff2394-60ef-4ffb-a5a3-f7988b56953c)





# Thorax CT Denoising

This project focuses on denoising Thorax CT (Computed Tomography) images using various image processing techniques and algorithms. The goal is to enhance the quality of CT images by reducing noise while preserving important details for accurate diagnosis and analysis.

## Code Overview

The code performs the following steps:

1. **Image Loading**: Load the Thorax CT image for denoising.

2. **Parameter Initialization**: Define the parameters for denoising, including values for noise reduction, template window sizes, search window sizes, sharpening parameters, filter methods, contrast enhancement methods, and resolution enhancement methods.

3. **Iterative Denoising and Enhancement**: Iterate through different combinations of denoising, sharpening, contrast enhancement, and resolution enhancement techniques. Apply these techniques to the input CT image and evaluate the results based on Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM).

4. **Select Best Parameters**: Select the combination of techniques that yields the highest PSNR and SSIM values, indicating the most effective denoising and enhancement.

5. **Visualization and Analysis**: Visualize the denoised and enhanced CT images along with the selected parameters. Display the PSNR and SSIM values for each combination.
