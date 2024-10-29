# image-convolution-and-edge-detection-using-sobel-operator
Edge Detection with Sobel Filter:

cv2.Sobel: Applies the Sobel edge detection filter to the grayscale image to detect edges in both horizontal (x) and vertical (y) directions.

Visualization: Displays the original image, edges detected in x-direction, y-direction, and the combined result using plt.imshow.

Gaussian Blurring:

cv2.GaussianBlur: Applies a Gaussian blur to the image to smooth it, which reduces noise and detail.

Visualization: Shows both the original and blurred images side by side using plt.imshow.

Texture Analysis with Gabor Filters:

Gabor Filter: A Gabor filter is applied to the grayscale image to detect textures at different orientations (0, 45, 90, and 135 degrees).

Parameters: ksize (size of the filter), sigma (standard deviation of the Gaussian), theta (orientation), lambd (wavelength), gamma (aspect ratio), and psi (phase offset).

Visualization: Displays the original and filtered images for each orientation using plt.imshow
Laplacian Edge Detection:
Read the Image: Loads the image in grayscale.

Laplacian Edge Detection: Applies the Laplacian filter to detect edges.

Convert to uint8: Converts the result to an 8-bit image.

Display: Shows the original image and the edge-detected image side by side.

Fourier Transform:
Read the Image: Loads the image in grayscale.

Fourier Transform: Computes the Fourier transform of the image to switch from spatial domain to frequency domain.

Shift and Spectrum: Shifts the zero frequency to the center and calculates the magnitude spectrum.

Display: Shows the original image and its magnitude spectrum.

Non-Maximum Suppression:
Read the Image: Loads the image in grayscale.

Gaussian Blur: Smooths the image using Gaussian Blur.

Compute Gradients: Uses Sobel filters to get the gradients.

Non-Maximum Suppression: Keeps only the local maxima of the gradients to thin out the edges.

Display: Shows the original image and the result after non-maximum suppression.
