YouTube Data Harvesting and Analysis
Welcome to the YouTube Data Harvesting and Analysis project! This repository contains a Python script that empowers you to collect and analyze YouTube channel data. It utilizes data from both MongoDB and MySQL databases, allowing you to gain insights into video statistics, comments, and popular channels. Whether you're a data enthusiast or a content creator looking for valuable insights, this script is designed to provide you with actionable information.

Features
Data Collection: Retrieve channel statistics, video details, and comments using YouTube Data API and store them in MongoDB.
Interactive Dashboard: Use the Streamlit interactive dashboard to perform queries, visualize data, and gain insights.
SQL Database Integration: Migrate collected data from MongoDB to MySQL for advanced analysis and reporting.
Data Visualization: Leverage Plotly Express to create interactive visualizations directly in the dashboard.
Data Deletion: Remove channel data from MongoDB Atlas or MySQL database as needed.
Getting Started
Install Dependencies: Install the necessary Python libraries by running:

bash
Copy code
pip install google-api-python-client pymongo mysql-connector-python sqlalchemy pandas plotly streamlit
API Keys and Database Setup:

Acquire a YouTube Data API key.
Set up a MongoDB Atlas cluster and a MySQL database with credentials (root, password: 1234). Modify the connection strings in the script.
Running the Script:

Run the script by executing: streamlit run your_script_name.py.
Use the Streamlit dashboard to interact with the script's functionalities.
Dashboard Usage
Collect Channel Data:

Enter a channel ID to retrieve and store channel statistics, playlist information, and video details in MongoDB.
Migration and Analytics:

Migrate MongoDB data to MySQL for in-depth analysis.
Utilize the dashboard to perform queries, visualize data, and gain insights.
Delete Data:

Delete specific channel data from MongoDB Atlas or MySQL database using the provided buttons in the dashboard.
Queries and Visualization
The Streamlit dashboard offers a range of queries and visualization options:

List all videos and their corresponding channels.
Identify channels with the most videos and their video counts.
Display the top 10 most viewed videos and their channels.
Show comment counts for each video along with their video names.
Highlight videos with the highest number of likes and their channels.
List videos with the total number of likes and their channels.
Visualize the total number of views for each channel.
Display channels and video counts for videos published in 2022.
Showcase the average duration of videos in each channel.
Identify videos with the highest number of comments along with their channels.
Data Deletion
Use the provided buttons in the dashboard to delete specific channel data:

Delete channel data from MongoDB Atlas.
Delete channel data from MySQL database.
Note
Ensure that you have valid YouTube API credentials and properly set up MongoDB and MySQL databases.
Comply with YouTube's API terms of service, manage API quotas, and handle limits responsibly.
Feel free to customize and extend the script to suit your specific requirements.
Contact
For any questions, support, or suggestions, feel free to contact [Your Name] at [your.email@example.com].

Disclaimer: This script is intended for educational and learning purposes. Ensure responsible usage and adherence to YouTube's API usage policies.

Thank you for considering this README as a guide for your project. Feel free to customize and expand upon it to match your project's specific needs. Good luck with your project on GitHub!
