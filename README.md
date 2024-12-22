# Wildfire-Risk-Calculator
# NOTE:-
*******THIS PROJECT CAN ONLY BE USED 36 TIMES*******


📌Change directory: In CMD OR TERMINAL change the directory to the path where the zip is unzipped by using the following code:
👨‍💻"cd path/to/main.py"

📌Set Up a Virtual Environment: Create and activate a virtual environment to manage the project dependencies.
# use COMMAND PROMPT(IN WINDOWS) OR TERMINAL (IN MAC)
👨‍💻 Enter the following code1 :
python -m venv env
👨‍💻 Enter the following code2:
#On MAC, use 'source env/bin/activate'  # On Windows, use 'env\Scripts\activate'

📌Install Required Libraries: Install all the necessary Python libraries specified in the requirements.txt file.
👨‍💻 #using the following code in CMD OR TERMINAL:
pip install -r requirements.txt

📌Brief Description of Each File:
📍main.py: 
The main script for the project. It includes functions for fetching weather data, preprocessing data, training the machine learning model, calculating fire risk, and visualizing the results using Streamlit.
📍requirements.txt: 
A file listing all the dependencies required to run the project. This includes libraries such as pandas, numpy, requests, scikit-learn, matplotlib, seaborn, streamlit, and geopandas.
📍requirements.txt:
A file containing all the API keys required to get the output from the program

📌Instructions for Running the Code

📍Ensure All Dependencies Are Installed: 
Make sure all libraries listed in the requirements.txt file are installed in your virtual environment.
👨‍💻 #use the following code in CMD OR TERMINAL
pip install -r requirements.txt

📍Run the Streamlit App: 
Execute the main script using Streamlit to start the web application.
👨‍💻 #use the following code in CMD OR TERMINAL
streamlit run main.py

📍Usage Instructions
🎯Input API Keys and Location:
When the Streamlit app launches, provide the required API keys from API_key.txt.
Enter the desired location, click "Find Location", and select from the dropdown.

🎯Calculate Fire Risk:
Follow on-screen instructions to calculate and visualize the fire risk.

📌Dependencies and Special Requirements
📍Python: Make sure you have Python installed (preferably Python 3.7 or later).

📍API Keys: Obtain an API key from API key.txt file to fetch weather data and other details.

📍Libraries: The following libraries are required and should be listed in the requirements.txt file:
📀streamlit==0.89.0
📀pandas==1.3.3
📀numpy==1.21.2
📀scikit-learn==0.24.2
📀xgboost==1.4.2
📀folium==0.12.1
📀requests==2.26.0
📀matplotlib==3.4.3
📀seaborn==0.11.2

📌AI Tools Used
📍Copilot by Microsoft: 
This AI tool was used to provide suggestions for the project setup and execution.
