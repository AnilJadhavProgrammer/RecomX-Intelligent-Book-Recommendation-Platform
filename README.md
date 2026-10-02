# RecomX — Intelligent Book Recommendation Platform

RecomX is a machine learning-based book recommendation system that provides relevant book suggestions based on book information and user preferences.

The project demonstrates a recommendation workflow using Python and pre-trained model/data files to generate book recommendations.

## Overview

The system is designed to help users discover books by providing recommendations based on the selected book and available book-related information.

The project uses a Python application with serialized model/data files to generate recommendations.

## Features

* Book recommendation
* Search/select a book for recommendations
* Recommendation based on book information and ratings
* Pre-trained recommendation model
* Interactive application interface
* Fast recommendation generation

## Recommendation Workflow

```text
User Selects a Book
        ↓
Book Information Processing
        ↓
Recommendation Model
        ↓
Similarity / Rating Analysis
        ↓
Recommended Books
```

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle
* Machine Learning

## Project Structure

```text
RecomX-Intelligent-Book-Recommendation-Platform/
│
├── app.py
├── book_name.pkl
├── final_rating.pkl
├── model.pkl
├── requirements.txt
├── setup.py
└── README.md
```

### File Description

| File               | Description                                            |
| ------------------ | ------------------------------------------------------ |
| `app.py`           | Main application used to run the recommendation system |
| `book_name.pkl`    | Serialized book-related data used by the application   |
| `final_rating.pkl` | Serialized rating data used for recommendations        |
| `model.pkl`        | Saved recommendation model/data                        |
| `requirements.txt` | Python dependencies required by the project            |
| `setup.py`         | Project setup configuration                            |
| `README.md`        | Project documentation                                  |

## Complete Setup and Usage Flow

### 1. Prerequisites

Make sure the following are installed:

* Python 3.x
* pip
* Git

Verify the installation:

```bash
python --version
pip --version
```

### 2. Clone the Repository

```bash
git clone <repository-url>
cd RecomX-Intelligent-Book-Recommendation-Platform
```

### 3. Create a Virtual Environment

Creating a virtual environment keeps project dependencies isolated from other Python projects.

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

Install the dependencies provided by the project:

```bash
pip install -r requirements.txt
```

If required, the project can also be installed using:

```bash
pip install .
```

### 5. Verify Required Files

Before starting the application, make sure the following files are present:

```text
app.py
book_name.pkl
final_rating.pkl
model.pkl
```

These serialized files are required by the recommendation application.

### 6. Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

After the application starts, Streamlit will provide a local URL in the terminal.

Open the displayed URL in a web browser.

## Complete Execution Flow

```text
Clone Repository
       ↓
Create Virtual Environment
       ↓
Activate Virtual Environment
       ↓
Install Dependencies
       ↓
Verify Model/Data Files
       ↓
Run app.py
       ↓
Open Streamlit Application
       ↓
Select a Book
       ↓
Generate Recommendations
       ↓
View Recommended Books
```

## Sample Usage

After launching the application:

1. Open the Streamlit application in your browser.
2. Select or enter a book from the available book list.
3. Submit the selection.
4. RecomX processes the selected book using the saved recommendation model/data.
5. The application displays recommended books.

Example workflow:

```text
Selected Book
    ↓
"The Alchemist"
    ↓
Recommendation Engine
    ↓
Recommended Books
    ├── Book 1
    ├── Book 2
    ├── Book 3
    ├── Book 4
    └── Book 5
```

The displayed recommendations depend on the data and trained model included in the repository.

## Model and Data Files

RecomX uses serialized `.pkl` files to store the data/model required by the application.

```text
book_name.pkl
      ↓
Book Information

final_rating.pkl
      ↓
Rating Information

model.pkl
      ↓
Recommendation Model / Model Data
```

These files allow the application to load the required recommendation resources without rebuilding the model every time the application starts.

## Skills Demonstrated

* Python Programming
* Machine Learning
* Recommendation Systems
* Data Processing
* Model Persistence
* Streamlit Application Development
* Pandas
* NumPy
* Scikit-learn

## Learning Outcomes

This project provided practical experience in building and deploying a recommendation-based Python application.

Key learning areas include:

* Working with recommendation-system data
* Preparing data for recommendations
* Using serialized machine learning/model files
* Loading pre-trained resources
* Building an interactive Streamlit application
* Connecting a recommendation model with a user interface
* Generating recommendations based on user input

## Troubleshooting

### `ModuleNotFoundError`

Install the project dependencies again:

```bash
pip install -r requirements.txt
```

### Streamlit command not found

Install Streamlit manually:

```bash
pip install streamlit
```

Then run:

```bash
streamlit run app.py
```

### Model/Data File Not Found

Make sure these files are present in the expected project directory:

```text
book_name.pkl
final_rating.pkl
model.pkl
```

### Application Does Not Start

Make sure the virtual environment is activated and all required dependencies are installed.

Then run:

```bash
streamlit run app.py
```

## Disclaimer

This project is intended for educational and portfolio purposes. The recommendations are generated from the available dataset and recommendation model and may not always match an individual reader's preferences.

## Author

**Anil Jadhav**
