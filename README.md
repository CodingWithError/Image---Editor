# Image Editor Project

This Java-based image editor allows users to perform various image manipulation operations such as:

- Viewing pixel values
- Converting an image to grayscale
- Adjusting image brightness
- Transposing (rotating) the image to the left or right
- Inverting the image horizontally or vertically
- Applying a blur effect

The image editor will take an input image file (e.g., `sample.jpg`) and produce the result in an output image file (`output.jpg`).

## Features

1. **View Pixel Values**: Prints out the pixel values of the input image.
2. **Convert to Grayscale**: Converts the input image to grayscale.
3. **Increase Brightness**: Adjusts the brightness of the input image by a specified percentage.
4. **Right Transpose**: Rotates the image to the right (90 degrees clockwise).
5. **Left Transpose**: Rotates the image to the left (90 degrees counter-clockwise).
6. **Invert Horizontally**: Flips the image along the horizontal axis.
7. **Invert Vertically**: Flips the image along the vertical axis.
8. **Blur Image**: Applies a blur effect to the input image based on pixel grouping.

## Prerequisites

- Java Development Kit (JDK) installed.
- `javax.imageio.ImageIO` library (part of the standard JDK) is required for image reading/writing.
- An image file named `sample.jpg` or any other image file you'd like to manipulate.

## How to Run the Program

1. **Clone the Project**
   - Clone the repository or download the source code.
   
2. **Compile the Code**
   - Open a terminal in the project directory.
   - Compile the program using the following command:
     ```bash
     javac imageeditor.java
     ```

3. **Run the Program**
   - After compiling, run the program with the command:
     ```bash
     java imageeditor
     ```

4. **Provide Input**
   - Enter the filename of the image you'd like to manipulate (e.g., `sample.jpg`).
   - You will be prompted to select one of the following options:
     ```
     Enter 1 for Pixel value
     Enter 2 for Convert IMAGE GRAY
     Enter 3 for Increase IMAGE BRIGHTNESS
     Enter 4 for Right Transpose Image
     Enter 5 for Left Transpose Image
     Enter 6 for Invert Horizontal Image
     Enter 7 for Invert Vertical Image
     Enter 8 for Blur Image
     ```

5. **Save the Output**
   - Depending on the option selected, the manipulated image will be saved as `output.jpg` in the project directory.

### Example Usage

- To convert the image to grayscale:

```bash
3
```
![sample](https://github.com/user-attachments/assets/91ea2f56-490d-403f-901c-89fe0a072a53)
![output](https://github.com/user-attachments/assets/181ce3e0-2ff1-44ec-ba7b-0fc20c7d2cb9)

## Output

The manipulated image will be shown in `output.jpg` in the same directory.
