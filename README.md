# Chi-Square-Histogram-Comparison-for-PPM-Images
PPM Image Similarity Using Chi-Square Histogram Analysis
This C program compares two PPM images using a chi-square statistic based on their RGB color histograms. The program allows users to specify a histogram bin factor (2, 4, 8, or 16) to control the granularity of the comparison, then calculates and outputs the chi-square value to measure image similarity.

Features
Chi-Square Histogram Comparison: Computes the chi-square statistic for comparing two images based on their RGB histograms.
Flexible Histogram Size: Users can adjust the histogram size with bin factors of 2, 4, 8, or 16 for finer or coarser analysis.
PPM Image Support: Works specifically with PPM (Portable Pixel Map) image format.
Technologies Used
C Programming Language
PPM Image Format
How It Works
Load PPM Images: The program loads two PPM images from files.
Histogram Calculation: It computes RGB histograms for both images with customizable bin sizes.
Chi-Square Calculation: The program calculates the chi-square statistic to measure the difference between the histograms of the two images.
Output Results: It outputs the chi-square value, histogram size, and total pixels used in the comparison.
Requirements
A C compiler (e.g., GCC, Visual Studio).
Two PPM images for comparison.
How to Use
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/ppm-image-chi-square-comparison.git
Compile the program:

bash
Copy code
gcc -o image_comparison image_comparison.c -lm
Run the program:

bash
Copy code
./image_comparison
Enter the filenames for the two PPM images when prompted, along with the desired histogram bin factor.

Example:

bash
Copy code
Enter first image file name: image1.ppm
Enter second image file name: image2.ppm
Enter Histogram size (2, 4, 8, or 16): 4
The program will output:

The chi-square value of the image comparison.
The histogram size.
The total number of pixels processed.
Example Output
bash
Copy code
Enter first image file name: image1.ppm
Enter second image file name: image2.ppm
Enter Histogram size (2, 4, 8, or 16): 4
First image: image1.ppm, Second image: image2.ppm
Histogram size = 64
Total Pixels = 600000
Chi-square = 0.325
Contributing
Feel free to fork this repository, submit issues, and send pull requests for bug fixes, enhancements, or other improvements!

License
This project is open source and available under the MIT License.
