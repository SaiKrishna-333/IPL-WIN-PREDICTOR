Cricket Match Win Probability Predictor

**Cricket Match Win Probability Predictor** is a web application built using Flask that predicts the probability of a team winning a cricket match based on live 				match data. The application uses a pre-trained machine learning model to calculate the win and loss probabilities for the batting team.

Features
		Win Probability Prediction
				Predicts the probability of the batting team winning or losing the match.
				Takes into account factors such as:
						Batting team
						Bowling team
						City where the match is being played
						Target score
						Current score
						Balls left
						Wickets remaining
		User-Friendly Interface:
				Simple and intuitive form to input match details.
				Displays the win and loss probabilities in a clean and readable format.
		Machine Learning Model:
				Uses a pre-trained machine learning model (ra_pipe.pkl) to make predictions.
				The model is trained on historical cricket match data.

Technologies Used
		Backend:
				Python
				Flask (for web application framework)
		Frontend:
				HTML
				CSS
		Machine Learning:
				Scikit-learn (for model training and prediction)
				Pandas (for data manipulation)
		Other Tools:
				Pickle (for model serialization and deserialization)

File Structure
cricket-win-predictor/
├── app.py               # Flask application (main backend logic)
├── ra_pipe.pkl          # Pre-trained machine learning model
├── templates/           # HTML templates for the frontend
│   ├── index.html       # Home page with input form
│   └── result.html      # Result page displaying win/loss probabilities
├── README.md            # Project documentation
└── requirements.txt     # List of Python dependencies (optional)

Usage
		Home Page:
				Open the application in your browser.
				Fill in the form with the following details:	
						Batting Team
						Bowling Team
						City
						Target Score
						Current Score
						Balls Left
						Wickets Remaining
					Click the "Predict" button.
		Result Page:
				The application will display the probability of the batting team winning or losing the match.
