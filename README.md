/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Header Section */
header {
    background-color: #006400; /* Dark Green */
    color: white;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    font-size: 3em;
    margin: 0;
    font-weight: bold;
    letter-spacing: 2px;
}

header p {
    font-size: 1.2em;
    margin-top: 10px;
}

/* Main Content Section */
.container {
    padding: 40px 20px;
    text-align: center;
    background-color: #fff;
    border-radius: 8px;
    margin: 30px auto;
    max-width: 800px;
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
}

.container h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

.container p {
    font-size: 1.2em;
    line-height: 1.6;
    color: #555;
}

/* Prediction Form Section */
.prediction-form {
    background-color: #f0f8ff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.prediction-form h3 {
    margin-bottom: 20px;
}

.prediction-form input, 
.prediction-form select, 
.prediction-form button {
    padding: 10px;
    margin: 10px 0;
    width: 100%;
    max-width: 400px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 1em;
}

.prediction-form button {
    background-color: #f5b300; /* Yellow */
    border: none;
    color: white;
    cursor: pointer;
    transition: background-color 0.3s;
}

.prediction-form button:hover {
    background-color: #ff9c00;
}

/* Footer Section */
.footer {
    background-color: #333;
    color: white;
    padding: 15px 0;
    text-align: center;
    font-size: 1em;
    margin-top: 40px;
}
