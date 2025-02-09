# depth-anything-v2.neu

## Overview
Generates a depth map from an input image using the Depth Anything V2 model. This module leverages ComfyUI's implementation of the Depth Anything V2 algorithm to create high-quality depth estimations.

### Module Inputs
- **image**: Input image to generate depth map from (BufferedImage)

### Module Outputs
- **depth**: Generated depth map as a grayscale image (BufferedImage)

### Notes
- Uses the depth_anything_v2_vitl_fp32.safetensors model
- The model will be automatically downloaded if not present
- Output depth map is grayscale where lighter values represent areas closer to the camera and darker values represent areas further away
