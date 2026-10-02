# RecomX — Intelligent Book Recommendation Platform

RecomX is a machine learning-based book recommendation platform that recommends books based on **book ratings and author-related information**.

The project is designed to provide relevant book recommendations through a simple and user-friendly application interface.

## Features

* Book recommendation based on available book data
* Rating-based recommendation
* Author-based recommendation
* Pre-trained recommendation model
* Simple and interactive application interface
* Fast recommendation generation using serialized model files

## Project Workflow

```text
Book Data
    ↓
Data Preprocessing
    ↓
Feature Preparation
    ↓
Recommendation Model
    ↓
Book Selection
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
* Recommendation Systems

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

| File               | Description                   |
| ------------------ | ----------------------------- |
| `app.py`           | Main application file         |
| `book_name.pkl`    | Stored book information       |
| `final_rating.pkl` | Processed rating data         |
| `model.pkl`        | Trained recommendation model  |
| `requirements.txt` | Required Python dependencies  |
| `setup.py`         | Project/package configuration |
| `README.md`        | Project documentation         |

## How It Works

RecomX uses book-related information and rating data to generate recommendations.

1. The user interacts with the application.
2. The application processes the selected book or related information.
3. The recommendation model uses the available book and rating data.
4. Relevant books are identified.
5. Recommended books are displayed to the user.

## Installation

Clone the repository:

```bash
git clone https://github.com/AnilJadhavProgrammer/RecomX-Intelligent-Book-Recommendation-Platform.git
```

Navigate to the project directory:

```bash
cd RecomX-Intelligent-Book-Recommendation-Platform
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the application using:

```bash
streamlit run app.py
```

The application will open in your default browser.

## Use Cases

* Discovering books based on ratings
* Finding books associated with preferred authors
* Exploring similar or relevant books
* Building a personalized reading recommendation workflow

## Future Enhancements

* User-based personalized recommendations
* Improved recommendation algorithms
* Book genre-based filtering
* User login and recommendation history
* Integration with external book APIs
* Deployment as a cloud-based recommendation platform

## Skills Demonstrated

* Python Programming
* Machine Learning
* Recommendation Systems
* Data Preprocessing
* Data Analysis
* Model Serialization
* Streamlit Application Development

## Author

**Anil Jadhav**

GitHub: [AnilJadhavProgrammer](https://github.com/AnilJadhavProgrammer)

## License

This project is intended for educational and portfolio purposes.
