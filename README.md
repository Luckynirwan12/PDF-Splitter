# PDF Splitter

## 📝 Description
A simple Python script to split a PDF file into two parts at a specific page number using the PyPDF2 library.

## 🚀 Features
- Split any PDF into two separate parts at a user-defined page.

- Automatically creates the output directory if it doesn't exist.

- Easy to use — just run and enter the page number to split at.

- Lightweight and compatible with Jupyter, Colab, or command line.

## 🛠️ Requirements
- Python 3.x

- `PyPDF2`

Install with:

    !pip install PyPDF2

## 📥 Input
The script takes a single PDF file as input. You need to specify:

- The full file path to the PDF you want to split.
  
Example:

        /content/Research.pdf

- The page number where you want to split the file.

   - Page numbers start from `1` (not 0).

   - For example, entering `3` will include pages 1–3 in the first file, and the rest in the second.
 
## 📁 Output
The script saves two new PDF files:

    output/
       ├── part1.pdf
       └── part2.pdf


