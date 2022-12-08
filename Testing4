# Import libraries
from flask import Flask, render_template

# Create an instance of Flask
app = Flask(__name__)

# Define a route for the home page
@app.route('/')
def home():
    # Render a template
    return render_template('index.html')

# Run the app
if __name__ == '__main__':
    app.run(debug=True)
