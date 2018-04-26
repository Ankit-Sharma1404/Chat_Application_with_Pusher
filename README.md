# STEP FOR CREATING CHAT APPLICATION FOR MULTIPLE USERS. <br>

(1.) login in pusher.com then select "Java Scriot" for client side and "python" for server side. <br>
(2.) we install pusher :- "pip install pusher" <br>
(3.) Now pipenv install flask-sqlalchemy <br>
(4.) Now we have to download SQLite from " https://www.sqlite.org" website & (download Precompiled Binaries for Windows) 
	 to work with SQLite on Windows, you download the command-line shell program. 
	 The downloaded file is ZIP format and its size is quite small. 
	 Extract the content of the file where you want and you should see the sqlite3.exe folder. <br>
	 To verify the installation, you perform the following steps: <br>
	 First, open the command line window and navigate to the folder where you unzip your "sqlite3.exe" file. <br>
	 Second, enter sqlite3, for check the sqlite is working or not. Now type in command prompt "sqlite3 messages.db" for creating a database. <br>
     (5.) open the python script editor and "import from app import db" for importing your "app,py" file to database. And type "db.create_all()" for creating database. <br>
     (6.) Run you Application where your save it "python app.py"
