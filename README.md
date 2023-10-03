# Image Resizer

This Python script provides a graphical user interface (GUI) for resizing images to custom dimensions. It uses the Tkinter library for the GUI and the Pillow library for image processing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Before using this image resizer, make sure you have Python 3.x installed on your machine. You can check your Python version by running:

`
python --version`


To set up the application, follow these steps:

Clone or download the source code from this GitHub repository.


`git clone https://github.com/biswadeep-roy/image-resizer.git
`

Navigate to the project directory.

`cd image-resizer
`

Install the required Python packages (Tkinter and Pillow) if you haven't already. You can use pip for this:

`pip install tkinter pillow
`

#Usage
To run the image resizer program, execute the following command in the project directory:

`python image_resizer.py
`
The GUI will appear with a "Choose File" button. Click on the button to select the image file you want to resize. Once you have selected the file, you can specify the desired dimensions of the resized image by entering the width and height values in pixels.

Click the "Resize" button to resize the image to the specified dimensions. The resized image will be saved in the same directory as the original image file with "_resized" appended to the filename.


## Contributing
Contributions to this project are welcome. If you'd like to contribute, follow these steps:

Fork the repository to your GitHub account.

Create a new branch for your changes:

`git checkout -b your-feature-branch
`

Make your changes and commit them with descriptive commit messages.

Push your changes to your forked repository:

`git push origin your-feature-branch
`

Create a pull request from your branch to the main repository for review.
 
## License

This project is licensed under the MIT License. See the LICENSE file for more information.
