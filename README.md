# WhatsApp Chat Analysis

This project is designed to analyze WhatsApp chat data to provide insights such as message frequency, word usage, media sharing, and more. The analysis is visualized using graphs and charts to make it easier to understand the trends within the chat data.

## Features

- **Statistics Overview**:
  - Total number of messages
  - Total number of words
  - Number of media messages shared
  - Number of links shared

- **Timeline Analysis**:
  - Monthly timeline of messages
  - Daily timeline of messages

- **Activity Maps**:
  - Most active days of the week
  - Most active months

- **WordCloud**:
  - Visualization of most used words in the chat

- **Most Common Words**:
  - List of the most commonly used words


# Project Structure
The project consists of the following files:

1. app.py: Main Streamlit application file where the app logic resides.
2. preprocessor.py: Module for preprocessing the WhatsApp chat data.
3. helper.py: Module containing helper functions for data analysis and visualization.
4. stop_hinglish.txt: File containing stop words for filtering out common words.

# Technologies Used
1. Python
2. Streamlit: For creating the interactive web app
3. Pandas: For data manipulation and analysis
4. Matplotlib & Seaborn: For data visualization
5. urlextract: For extracting URLs from messages

## How to Use

1. Clone the repository
2. Install the required dependencies:
   pip install -r requirements.txt
3. Run the Streamlit app:
   streamlit run app.py
4. Upload your WhatsApp chat file
5. Analyze the Chat 

