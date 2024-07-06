MSC_lib
MSC_lib is a Python library designed for basic image processing and fundamental calculator operations.

Installation
To install MSC_lib, follow these steps:

Clone the repository:

bash
Kodu kopyala
git clone https://github.com/yourusername/MSC_lib.git
Navigate to the MSC_lib directory:

bash
Kodu kopyala
cd MSC_lib
Install the required dependencies:

bash
Kodu kopyala
pip install -r requirements.txt
Usage
Calculator Functions
You can perform basic calculator operations using the calculate function. Here are the supported operations:

Addition (add)
Subtraction (sub)
Multiplication (multi)
Division (divide)
Example usage:

python
Kodu kopyala
result = calculate("add", 10, 5)
print(result)  # Output: 15
Image Processing Functions
MSC_lib provides several image processing functions. Here are a few examples:

Capturing an Image from Camera
python
Kodu kopyala
image = cam_take()
Saving an Image
python
Kodu kopyala
image_save("my_image", image)
Converting an Image to Grayscale
python
Kodu kopyala
gray_image = image_gray(image)
Adding Text to an Image
python
Kodu kopyala
image_with_text = image_txt(image, "Hello, MSC_lib!", (50, 50))
Utility Functions
MSC_lib also includes some utility functions:

Checking Palindrome
python
Kodu kopyala
result = pal("radar")
print(result)  # Output: True
Extracting the First Word
python
Kodu kopyala
result = first_word("Hello world!")
print(result)  # Output: "Hello"
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to OpenCV for image processing capabilities.
Special thanks to the Python community for inspiration.
