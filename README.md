
YouTube Data Harvesting and Analysis 
Welcome to the YouTube Data Harvesting and Analysis project! This repository contains a Python script that empowers you to collect and analyze YouTube channel data. It utilizes data from both MongoDB and MySQL databases, allowing you to gain insights into video statistics, comments, and popular channels. Whether you're a data enthusiast or a content creator looking for valuable insights, this script is designed to provide you with actionable information.  Features 1. Data Collection: Retrieve channel statistics, video details, and comments using YouTube Data API and store them in MongoDB. 2. Interactive Dashboard: Use the Streamlit interactive dashboard to perform queries, visualize data, and gain insights. 3. SQL Database Integration: Migrate collected data from MongoDB to MySQL for advanced analysis and reporting. 4. Data Visualization: Leverage Plotly Express to create interactive visualizations directly in the dashboard. 5. Data Deletion: Remove channel data from MongoDB Atlas or MySQL database as needed. 
Getting Started Install Dependencies: Install the necessary Python libraries 
API Keys and Database Setup: Acquire a YouTube Data API key. Set up a MongoDB Atlas cluster and a MySQL database with credentials (root, password: 1234). Modify the connection strings in the script. 
Running the Script: Run the script by executing: streamlit run your_script_name.py. Use the Streamlit dashboard to interact with the script's functionalities. 



Dashboard Usage 
1.	Collect Channel Data: Enter a channel ID to retrieve and store channel statistics, playlist information, and video details in MongoDB. 
2.	Migration and Analytics: Migrate MongoDB data to MySQL for in-depth analysis. Utilize the dashboard to perform queries, visualize data, and gain insights. 
3.	Delete Data: Delete specific channel data from MongoDB Atlas or MySQL database using the provided buttons in the dashboard.

Queries and Visualization The Streamlit dashboard offers a range of queries and visualization options:  1. List all videos and their corresponding channels. 2. Identify channels with the most videos and their video counts. 3. Display the top 10 most viewed videos and their channels. 4. Show comment counts for each video along with their video names. 5. Highlight videos with the highest number of likes and their channels. 6. List videos with the total number of likes and their channels. 7. Visualize the total number of views for each channel. 8. Display channels and video counts for videos published in 2022. 9. Showcase the average duration of videos in each channel. 10.Identify videos with the highest number of comments along with their channels. 
Data Deletion Use the provided buttons in the dashboard to delete specific channel data:  1. Delete channel data from MongoDB Atlas. 2. Delete channel data from MySQL database. 
Note 1. Ensure that you have valid YouTube API credentials and properly set up MongoDB and MySQL databases. 2. Comply with YouTube's API terms of service, manage API quotas, and handle limits responsibly. 3. Feel free to customize and extend the script to suit your specific requirements. 
Contact For any questions, support, or suggestions, feel free to contact Divahar Murugan at divahar2896@gmail.com.  
