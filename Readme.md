# Crop Prediction Web Application

This project is a web-based Crop Recommendation System that predicts the most suitable crop to grow based on various environmental and soil parameters. It uses a machine learning model trained on agricultural data to provide recommendations to farmers and agricultural professionals.

## Features
- User-friendly web interface built with Flask
- Predicts the best crop based on user input (N, P, K, temperature, humidity, pH, rainfall)
- Utilizes a trained machine learning model (`model.pkl`)
- Clean and modern UI with custom CSS and images

## How It Works
1. User enters soil and environmental parameters in the web form.
2. The app processes the input and uses the trained model to predict the recommended crop.
3. The result is displayed instantly on the web page.

## Project Structure
```
├── app.py                  # Main Flask application
├── model.py                # Model training and loading logic
├── model.pkl               # Trained machine learning model
├── Crop_recommendation.csv # Dataset used for training
├── requirements.txt        # Python dependencies
├── static/
│   ├── style.css           # Custom styles
│   └── crop4.jpg           # Image used in UI
└── templates/
	 └── index.html          # Main HTML template
```

## Getting Started
### Prerequisites
- Python 3.7+
- pip

### Installation
1. Clone the repository:
	```sh
	git clone https://github.com/hariiom08/Crop_prediction.git
	cd Crop_prediction
	```
2. Install dependencies:
	```sh
	pip install -r requirements.txt
	```
3. Run the application:
	```sh
	python app.py
	```
4. Open your browser and go to `http://127.0.0.1:5000/`

## Usage
- Enter the required parameters in the form and click "Predict" to get the recommended crop.

## Dataset
- The dataset (`Crop_recommendation.csv`) contains agricultural data with features like N, P, K, temperature, humidity, pH, rainfall, and the corresponding crop label.

## Model
- The model is trained using scikit-learn and saved as `model.pkl`.
- You can retrain the model using `model.py` if needed.

## License
This project is open-source and available under the MIT License.

## Acknowledgements
- [Scikit-learn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Pandas](https://pandas.pydata.org/)
- [Original Dataset Source](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

## Connect with Me
- [GitHub](https://github.com/hariiom08)
- [LinkedIn](https://www.linkedin.com/in/hariom-mandloi-6266732a3)

