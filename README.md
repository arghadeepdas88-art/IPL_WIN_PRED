<!DOCTYPE html>
<html>
<head>
    <title>IPL Win Predictor</title>
</head>
<body>
    <h1>🏏 IPL Win Predictor</h1>
    <p>This project predicts the winning probability of IPL teams based on match conditions like score, overs, wickets, and run rate.</p>

    <h2>Features</h2>
    <ul>
        <li>Predict winning chances between two teams</li>
        <li>Inputs: batting team, bowling team, score, overs, wickets, target</li>
        <li>Uses Machine Learning (Logistic Regression / Random Forest)</li>
        <li>Web app built using Streamlit</li>
    </ul>

    <h2>Tech Stack</h2>
    <ul>
        <li>Python</li>
        <li>Pandas, NumPy, Scikit-learn</li>
        <li>Streamlit for deployment</li>
    </ul>

    <h2>How to Run</h2>
    <ol>
        <li>Clone the repo:
            <pre>git clone https://github.com/your-username/ipl-win-predictor.git</pre>
        </li>
        <li>Install dependencies:
            <pre>pip install -r requirements.txt</pre>
        </li>
        <li>Run the app:
            <pre>streamlit run app.py</pre>
        </li>
    </ol>

    <h2>Example Output</h2>
    <pre>
Winning Probability:
Mumbai Indians: 65%
Chennai Super Kings: 35%
    </pre>

    <h2>License</h2>
    <p>MIT License</p>
</body>
</html>
