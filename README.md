# Recipe Recommendation System

This project implements a smart recipe recommendation system using Machine Learning (KNN algorithm) to suggest recipes based on user-specified nutrients and ingredients. The system is built with Python and features a user-friendly web interface powered by Flask.

## Features

- Recipe recommendations based on nutritional preferences
- Ingredient-based recipe search
- Interactive web interface
- K-Nearest Neighbors (KNN) algorithm for accurate recommendations
- Large dataset of diverse recipes

## Project Structure

```
recipe/
├── app.py                    # Flask web application
├── Recipe_Recommendation_System.ipynb  # Jupyter notebook with ML model
├── recipe_final (1).csv      # Dataset containing recipes
└── templates/                # HTML templates for web interface
```

## Prerequisites

- Python 3.7+
- Flask
- pandas
- scikit-learn
- numpy

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
cd recipe
```

2. Install required dependencies:
```bash
pip install flask pandas scikit-learn numpy
```

## Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to `http://localhost:5000`

3. Enter your desired nutritional values and ingredients to get personalized recipe recommendations

## Dataset

The project uses a comprehensive recipe dataset (`recipe_final (1).csv`) that includes:
- Recipe names
- Ingredients
- Nutritional information
- Cooking instructions

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project.

## License

This project is open source and available under the MIT License.
