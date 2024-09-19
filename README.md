# Amazon ML Challenge Project

## Overview
This project was developed for the Amazon ML Challenge, where our team ranked **413 out of 75,000 participants**, placing in the **top 0.55%**. The objective was to build a machine learning model that extracts specific entity values (such as weight, dimensions, etc.) from product images using OCR and regex-based pattern matching.

## Key Features
- **OCR with Pytesseract**: Used for text extraction from images.
- **Regex-based Entity Matching**: Applied regular expressions to identify specific entity values like weight, dimensions, and voltage.
- **Concurrent Processing**: Employed Python's `ThreadPoolExecutor` to speed up the extraction process by running tasks in parallel.
- **Data Preprocessing**: Preprocessed images to improve OCR accuracy, including grayscale conversion.
- **Final Output**: Results were generated in the required submission format and validated using custom sanity checks.

## Files
- **train.csv / test.csv**: Datasets with image links and corresponding entities.
- **extract_text_from_image()**: Function to extract text from images using OCR.
- **extract_entity_value_and_unit()**: Function to parse and extract specific entity values using regex.
- **Output**: The predictions were stored in a CSV file for submission.

## How to Run
1. Clone the repository.
2. Install the necessary dependencies listed in `requirements.txt`.
3. Run the script to process the test images and generate predictions.
4. Review the output files for extracted entity values.

## Acknowledgments
Special thanks to my teammates and mentors for their support throughout the challenge.

---

Feel free to expand on any section as needed!
