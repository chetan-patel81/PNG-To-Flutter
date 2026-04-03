# PNG-to-Flutter Converter

## Overview
The PNG-to-Flutter Converter is a tool designed to transform PNG images into Flutter widgets, enabling developers to utilize vectorized images in their applications while maintaining high performance.

## Features
- Converts PNG images to Flutter code.
- Supports run-length encoding (RLE) for efficient image compression.
- Generates easily customizable Flutter widgets.

## How to Use
1. Clone the repository: `git clone https://github.com/chetan-patel81/PNG-To-Flutter`
2. Navigate to the project directory: `cd PNG-To-Flutter`
3. Run the converter on your PNG file: `dart run converter.dart example.png`
4. The output will be a Dart file containing the Flutter widget code.

## Technical Details about Run-Length Encoding Compression
Run-length encoding (RLE) is a simple form of lossless data compression in which runs of data are stored as a single data value and count. This helps in reducing the file size of images without sacrificing quality, making it ideal for use in Flutter applications where performance is critical.

## Generated Flutter Code Structure
The generated Flutter code includes:
- A `StatelessWidget` with a `build` method.
- Color data for each pixel encoded using run-length encoding.
- Constructors for easy customization of widget properties.

## Supported Image Formats
- PNG
- JPG
- GIF (limited support)

## Limitations
- The tool currently only supports images with a limited color palette (up to 256 colors).
- Some complex PNG features such as transparency may not be fully supported.

## Requirements
- Dart SDK 2.12 or higher
- Flutter SDK 2.0 or higher

## Installation Instructions
1. Ensure that you have the Dart SDK and Flutter SDK installed.
2. Clone the repository: `git clone https://github.com/chetan-patel81/PNG-To-Flutter`
3. Navigate to the project directory: `cd PNG-To-Flutter`
4. Install necessary packages: `flutter pub get`

## Usage Instructions
To use the PNG-to-Flutter converter, run the following command in the terminal:
```
dart run converter.dart input_image.png
```
Replace `input_image.png` with the path to your PNG file. The output will be a Dart file in the same directory.

---

For any issues or contributions, feel free to raise an issue or submit a pull request on the GitHub repository!