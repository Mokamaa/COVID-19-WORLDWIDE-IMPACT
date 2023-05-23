# COVID-19-WORLDWIDE-IMPACT
COVID-19 Data Scraping and Visualization
This project involves scraping COVID-19 data using ParseHub, exporting the extracted data to Excel for cleaning and manipulation, and visualizing the statistics using Tableau for interactive and dynamic visualizations. The process aims to provide an efficient and engaging way to explore and analyze COVID-19 data.

Table of Contents
Introduction
Requirements
Installation
Usage
License
Introduction
The COVID-19 pandemic has significantly impacted the world, and having access to accurate and up-to-date data is crucial for understanding the situation. This project leverages ParseHub, a powerful web scraping tool, to extract COVID-19 statistics from a specific website. The extracted data is then exported to Excel for cleaning and manipulation. Finally, Tableau, a popular data visualization tool, is used to create dynamic and interactive visualizations based on the cleaned data.

Requirements
To run this project, the following components are required:

ParseHub account and API key
Python 3.x
Pandas (for data manipulation and cleaning)
Openpyxl (for Excel integration)
Tableau Desktop (for data visualization)
Installation
Clone this repository to your local machine using the following command:
bashCopy code
git clone https://github.com/mokamaa/repo_name.git
Navigate to the project directory:
bashCopy code
cd repo_name
Install the required Python dependencies using pip:
Copy code
pip install -r requirements.txt
Install Tableau Desktop by following the official installation instructions provided by Tableau.
Usage
Sign in to ParseHub and create a new project using the website containing COVID-19 data.
Configure ParseHub to scrape the relevant information from the website, such as cases, deaths, and locations.
Set up the ParseHub API and obtain your API key.
Open the scraper.py file and update the API key and project token variables.
Run the scraper.py script using the following command:
Copy code
python scraper.py
This will trigger ParseHub to scrape the data and export it as a CSV file.
Open the exported CSV file using Microsoft Excel or any spreadsheet software to clean and manipulate the data as needed.
Utilize Pandas and Excel's features to perform data cleaning, filtering, and formatting operations.
Export the cleaned data from Excel to a format compatible with Tableau, such as CSV or Excel.
Launch Tableau Desktop and connect to the cleaned data source.
Use Tableau's drag-and-drop interface to create interactive and dynamic visualizations based on the COVID-19 data.
Apply filters, create dashboards, and add interactivity to the visualizations to provide a comprehensive analysis of the COVID-19 statistics.
Publish the Tableau visualizations to Tableau Server or Tableau Public for easy sharing and collaboration.
License
This project is licensed under the MIT License. Feel free to modify and adapt it according to your needs
