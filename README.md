# SMS Spam Detector

## Project Overview
This project is an SMS Spam Detector that uses Natural Language Processing (NLP) and a Naive Bayes classifier to classify messages as spam or ham (not spam). The dataset is preprocessed, vectorized, and used to train the model for effective spam detection.

## Steps to Run the Project

### 1. Clone the Repository
First, clone this GitHub repository to your local system:
```bash
git clone https://github.com/SwetankShandilya/SMS-Spam-Detector.git
cd SMS-Spam-Detector
```

### 2. Set Up the Virtual Environment (Optional but Recommended)
It’s a good practice to create a virtual environment before installing dependencies:
```bash
# For Windows
python -m venv env
env\Scripts\activate

# For macOS/Linux
python3 -m venv env
source env/bin/activate
```

### 3. Install Dependencies
Install all required Python packages using:
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
Run the Jupyter Notebook server:
```bash
jupyter notebook
```
Then, open **`SMS Spam Detector.ipynb`** in the Jupyter interface.

### 5. Run the Notebook
Execute all cells step by step to preprocess the dataset, train the model, and evaluate its performance.

### 6. Optional: Run on Google Colab
If you prefer running the notebook online, upload it to [Google Colab](https://colab.research.google.com/), and install dependencies using:
```python
!pip install -r requirements.txt
```

## Dependencies
All dependencies required for this project are listed in `requirements.txt`. Ensure you install them before running the notebook.

## Author
Swetank Shandilya

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

