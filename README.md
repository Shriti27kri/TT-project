# TT-project
This project is a simple attendance analysis system developed using Python and Pandas as part of a Minor-1 academic project. It analyzes seminar attendance data and displays attendance trends, tables, and statistical summaries using an interactive UI built with ipywidgets in Google Colab.

Users can select a seminar from a dropdown and view:
Attendance records
Attendance trend graph
Statistical summary

 Technologies Used
 Python
 Pandas – Data handling and analysis
 Matplotlib – Data visualization
 ipywidgets – Interactive UI components
 Google Colab – Execution environment

 Dataset Details
The dataset is created within the code and contains the following columns:

Column	Description
Date:	Date of the seminar
Seminar	:Seminar name (AI, ML, DS)
Student_Name:	Name of the student
Attendance:	Present / Absent

Features
Interactive dropdown to select seminar
Button-based analysis
Display of attendance data in table format
Line graph showing attendance trends
Statistical summary of attendance

 How to Run the Project
Open the notebook in Google Colab
Run all cells
Select a seminar from the dropdown
Click Analyze Attendance
View table, graph, and statistics

Project Level
Difficulty: medium
Category: Data Analysis
Purpose: Academic / Educational

 Brief Explanation of the Code
1️ Importing Libraries
  The required libraries such as Pandas, Matplotlib, and ipywidgets are imported to handle data, create plots, and build the UI.

2️ Creating the Dataset
  Attendance data is stored in a Python dictionary and converted into a Pandas DataFrame for easy analysis.

3️ Data Preprocessing
  The Attendance column is converted into numeric values (Present = 1, Absent = 0) to enable plotting and statistical calculations.

4️ User Interface
  A dropdown is used to select seminars
  A button triggers the analysis
  An output area displays results

5️ Analysis & Visualization
  Data is filtered based on the selected seminar
  A line graph shows attendance trends over time
  A statistical summary is generated using Pandas

6️ Output
  The output includes:
  Attendance table
  Line graph

