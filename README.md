**#GPS Toll-Based Simulation Project**
This project simulates a system to calculate toll charges based on vehicle locations using GPS data. It is designed for end users managing toll data, such as vehicle details, available balances, and last logged GPS data. The project uses Python and MySQL, with Flask for handling requests (GET and POST), Geopy for distance calculations, Folium for updating car balance details, and MySQL Connector for database interactions. An interactive web UI makes it easy for government employees to use.

**#Team Members:**
Anirudh K
Jaaswin S 
Edward Samuel L
Gokul P

**#How It Works**
1.	Car Registration: Register your car in the system.
2.	GPS Tracking: The system tracks the location of registered cars using GPS data.
3.	Toll Calculation: Tolls are calculated based on the location of the car.
4.	Backend Data storage: All the data are stored in backend database for future references

**#Requirements:**
1.	Python (recommended to using latest version)
2.	MySQL database (database schema provided in the project)
3.	Proper Web Browser (works best on Google Chrome, other browsers are also supported)

**#How to Use**
1.	Clone the project using Git
	•	Open your terminal (Command Prompt, Git Bash, etc.).
	•	Navigate to the directory where you want to clone the project.
	•		Use the following command to clone the repository:
			sh
			git clone <repository_url>
2.	Install the dependencies of Python packages:
	o	Ensure you have Python and pip installed on your system.Navigate to the cloned project directory:
	sh
	cd <project_directory>
	o	Replace <project_directory> with the name of your project directory.
	o	Install the dependencies listed in requirements.txt using pip:
	sh
		pip install -r requirements.txt
3.	Navigate to the respective file directory on your computer:
	o	If not already done in the previous step, navigate to the directory where app.py is 	located:
	Sh
		cd <path_to_app.py>
	o	Replace <path_to_app.py> with the path to the directory containing app.py.
4.	Start the application by using python app.py
		sh
		python app.py
5.	Open your web browser and go to http://127.0.0.1:5000/.
6.	Log in using your username and password if new then proceed with the registration of user.
		If you are a new user, proceed with the registration process.
		Follow the on-screen instructions to register and then log in with your username and password.
7.	Navigate to the home page:
		After logging in, you will be redirected to the home page of the application.
Enjoy using the application!

**#Important Notes:**
1.	Ensure Password Security:
	o	Make sure your passwords are secure. Use a combination of letters, numbers, and special characters.
	o	Avoid using easily guessable information such as birthdays or common words.
2.	Set a Strong Secret Key:
	o	A strong secret key is essential to protect your login sessions.
	o	In the Flask application, you can set the secret key in the configuration file. For example:	
	python
	app.config['SECRET_KEY'] = 'your_strong_secret_key'
	o	Make sure the secret key is complex and kept confidential.
3.	Database Flexibility:
	o	The project uses a simple MySQL database. However, you can modify the database schema if needed.
	o	If you prefer using a different database system, such as PostgreSQL or SQLite, you can update the database connection settings and modify the SQL queries accordingly.
