# Fleet-Monitoring-and-Data-Analytics-Dashboard

<br />
<p align="center">  
<br />
Dashboard:  <br/>
<img src="https://imgur.com/SiJFdbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />

<h2>Description</h2>
This project is a dynamic dashboard built with Python, Dash, SQLite, and GeoPandas. It monitors vehicle fleet data, visualizes real-time locations on an interactive map, and provides insights such as total distance traveled and average speed. It features a clean UI, hoverable map details, and a summary table, making it ideal for tracking and optimizing fleet operations.


<h2>Languages and Utilities Used</h2>


- Python
- SQLite
- Plotty Dash
- Pandas
- GeoPandas



<h2>Program walk-through:</h2>

<h3>Step 1: Setting Up Your Environment</h3>


**1.1 Install Python**

  1. Open a web browser and go to https://www.python.org/downloads/.

  2. Download the latest version for your operating system (Windows/Mac/Linux).

  3. Run the downloaded file to start the installation. During installation:

    - Check the box “Add Python to PATH” (very important!).
    - Click Install Now and wait for it to finish.
  
  4. Once installed, open your terminal:

    - **Windows**: Press Win + R, type cmd, and hit Enter.
    - **Mac**: Open "Terminal" from Applications > Utilities.
    - **Linux**: Open your terminal from the application menu.
  
  5. Check Python is installed by typing:

        bash
        >python --version

You should see something like Python 3.x.x.


**1.2 Install Required Tools**


You’ll need some libraries (think of them as extra tools for Python). Install them using pip (Python’s package manager):

1. Type the following commands one by one in your terminal:
After each command, wait until it says the installation is complete.
    bash
    >pip install pandas dash plotly sqlite3
    
    >pip install geopandas
    >
    >pip install pandas dash plotly

    >pip install matplotlib
    >pip show matplotlib




<h3>Step 2: Create the Project Folder</h3>

1. Open your file explorer.
2. Create a new folder called FleetDashboard anywhere on your computer (e.g., Desktop).
3. Inside this folder, create a new file named dashboard.py (this will hold your Python code).
- Make sure to copy the file path


<h3/>Step 3: Run the script</h3>

1. Write down the Python code, it can be with an app like Notepad++

<br />
Python Code:  <br/>
<img src="https://imgur.com/rjtP02W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />

2. Save the code in the folder you created
3. Open **Command Prompt** and navigate to the project directory
   
    bash
   >cd: C\Users\xx\xxx\xxx
   

4. Run the script

    bash
   >python dashboard.py

5. Dash is running on http://127.0.0.1:8050/


<h3/>Expected Output</h3>


1. Interactive Dashboard:

   
- Displays an interactive map of vehicle locations.

- Includes hover details for each vehicle (e.g., speed and distance)
  
- Shows a summary table of total distances and average speeds for all vehicles.














