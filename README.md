📊 Comprehensive Analysis of Squirrel Data in Central Park
🐿️ Overview
This project presents a comprehensive data analysis of squirrel sightings in New York City’s Central Park, based on the official 2018 Squirrel Census dataset.

We extracted insights about squirrel behavior, location preferences, activity levels across time of day, and physical characteristics like fur color and age.

🧠 What This Project Covers
📈 Fur Color Analysis
Total count of squirrels by fur color (Gray, Black, Cinnamon) and the most common color observed.

⏰ Time-of-Day Analysis
Comparison between AM and PM sightings to determine the most active time.

🧓🧒 Age Distribution
Counts and percentages of Adult vs. Juvenile squirrels.

🌲🏞️ Location Analysis
Determines whether squirrels are more frequently observed on the ground or above ground.

🏃‍♂️🍽️ Activity-Based Behavior
Tracks major squirrel activities: Running, Climbing, Chasing, Eating, Foraging — split by AM/PM.

📄 Report Export
Generates a fully formatted .docx report.

📊 Excel Summary Sheet
Exports an organized .xlsx file with all key metrics and behavioral stats.

📁 Project Files
File	Description
main.py	The main Python script that performs the full analysis.
2018_Central_Park_Squirrel_Census_...csv	The raw dataset used in the analysis.
Squirrel_Report.docx	Auto-generated Word report with all findings.
Squirrel_Summary.xlsx	Excel summary of all analysis metrics.

🛠️ Technologies Used
pandas – for data manipulation

numpy – for statistical calculations

python-docx – to export Word reports

openpyxl – for Excel export

Python 3.10+

📌 How to Run
Install requirements:

bash
Copy code
pip install pandas numpy python-docx openpyxl
Place your dataset CSV file in the same directory as main.py.

Run the script:

bash
Copy code
python main.py
Check outputs:

Squirrel_Report.docx for detailed report

Squirrel_Summary.xlsx for quick stats

📷 Sample Output
<img width="618" height="674" alt="image" src="https://github.com/user-attachments/assets/6242b905-4817-49e1-9adc-c381ec7911c0" />

🚀 Future Improvements
Add interactive maps using folium to show squirrel locations

Include visualization (bar charts, pie charts)

Export to PDF automatically

Create a Streamlit dashboard for web-based interaction

🧑‍💻 Author
Mohamed [a.k.a. Jimmy Neutron 🔬⚡]
Junior Data Analyst | Pythonista | Aspiring Data Scientist
Feel free to connect on LinkedIn or explore more on GitHub

📝 License
This project is under the MIT License.

