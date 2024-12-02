# Language Detection with Machine Learning

## Overview
This project focuses on building a machine learning model to detect the language of a given text. The dataset includes text samples in 22 languages, making it an excellent example of a multiclass classification problem. The Multinomial Naive Bayes algorithm is used due to its effectiveness in handling text data.

---

## Features
- **Dataset**: 22 languages with 1000 sentences each.
- **Text Preprocessing**: Converts text into numerical data using `CountVectorizer`.
- **Model Training**: Uses Multinomial Naive Bayes for multiclass classification.
- **User Input**: Detects the language of custom text entered by the user.

---

## Dataset
- The dataset contains text samples from 22 languages, including English, Spanish, Hindi, French, Arabic, and more.
- Each language has 1000 sentences, making it balanced and suitable for training.

### Source
The dataset is publicly available on [GitHub](https://raw.githubusercontent.com/amankharwal/Website-data/master/dataset.csv).

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/language-detection-analysis.git
cd language-detection-analysis
```
2. Install the required libraries:
```
bash
pip install -r requirements.txt
```
3. Download the dataset: The dataset will be automatically fetched via the provided link in the code.

---

## Usage
### Running the Project
1. Open the language_detection.py file in your IDE or terminal.
2. Run the script:
```
bash
python language_detection.py
```
3. Input custom text when prompted, and the model will predict the language.

---

## Project Workflow

### 1. Data Preprocessing
- Loads and checks the dataset for missing values.
- Converts text into numerical data using `CountVectorizer`.

### 2. Model Training
- Splits the data into training and testing sets.
- Trains a Multinomial Naive Bayes model for multiclass classification.

### 3. Model Evaluation
- Evaluates the model on the test set and calculates accuracy.

### 4. User Interaction
- Allows the user to input custom text for language detection.

---

## Results

- **Model Accuracy**: Approximately 95%.
- **Examples**:
  - **Input**: "देखकर अच्छा लगता है"  
    **Output**: `Hindi`
  - **Input**: "La vida es bella."  
    **Output**: `Spanish`

---

## Dependencies

- Python 3.7+
- Pandas
- NumPy
- Scikit-learn

---

## Repository Structure
```bash
language-detection-analysis/

│

├── language_detection.py  # Main script for the project

├── requirements.txt       # List of required Python libraries

├── README.md              # Project documentation

└── LICENSE                # License file

```
---

## Future Improvements

- Add more languages and larger datasets to improve accuracy.
- Develop a web or mobile app for real-time language detection.
- Handle scenarios where the text does not belong to any language in the dataset.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements or fixes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

- **Dataset**: Sourced from [Kaggle](https://www.kaggle.com/) and provided via [GitHub](https://github.com/).
- **Inspiration**: Inspired by an article by [Aman Kharwal](https://thecleverprogrammer.com/).
- **Libraries and Tools**: Special thanks to Scikit-learn and Python for making this project possible.

