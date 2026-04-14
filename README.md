# Image Upscaling Techniques and Evaluation

## Overview

This project focuses on implementing and evaluating different image upscaling techniques using Digital Signal Processing concepts. The objective is to improve image resolution while preserving visual quality and fine details.

## Aim

To explore various image upscaling techniques and evaluate their performance using objective and visual quality measures.

## Objective

Image upscaling increases image resolution while maintaining clarity and detail. Traditional enlargement methods often introduce blur and distortion. This project applies DSP-based enhancement techniques to overcome these limitations and generate sharper high-resolution images.

## Techniques Implemented

1. Gaussian Filtering
   - Generates a Gaussian kernel
   - Applies smoothing to reduce noise
   - Prepares the image for sharpening

2. Convolution Operation
   - Performs kernel-based filtering
   - Enhances structural image features
   - Used as a preprocessing step

3. Unsharp Masking
   - Improves edge clarity
   - Enhances contrast and sharpness
   - Combines original image with blurred version

4. Bicubic Interpolation Upscaling
   - Uses interpolation to increase image size
   - Scaling factor applied: 10×
   - Produces smoother and sharper results compared to nearest-neighbor scaling

## Workflow

- Input low-resolution image
- Apply Gaussian smoothing
- Perform convolution filtering
- Apply unsharp masking for sharpening
- Upscale image using bicubic interpolation
- Display enhanced high-resolution output

## Applications

- Media and Entertainment: Improves texture quality in games and digital graphics.
- Medical Imaging: Enhances MRI and CT scan resolution for better diagnosis.
- Remote Sensing: Improves satellite and aerial imagery for monitoring and analysis.
- Photography and Restoration: Restores old photographs and improves print-quality images.

## Tools and Technologies Used

- MATLAB / Image Processing Toolbox (imresize, convolution functions)
- Digital Signal Processing techniques
- Gaussian kernel filtering
- Bicubic interpolation

## Output

The processed image demonstrates:

- Improved resolution
- Enhanced sharpness
- Reduced blur
- Better visual detail preservation

## Results and Observations

The implemented upscaling pipeline significantly improves image clarity compared to traditional resizing methods. Combining filtering and sharpening before interpolation produces superior visual quality.

## Conclusion

This project presents a comparative framework for evaluating image upscaling techniques using DSP methods. The results highlight the effectiveness of combining Gaussian filtering, convolution, unsharp masking, and bicubic interpolation to enhance image resolution.

These techniques have practical applications in medical imaging, satellite imaging, digital restoration, and multimedia processing.
