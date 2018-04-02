# STEP FOR CREATING CHAT APPLICATION FOR MULTIPLE USERS.

(1.) login in pusher.com then select "React" for client side and "python" for server side 
(2.) we install pusher :- "pip install pusher" 
(3.) Now pipenv install flask-sqlalchemy

(4.) Now we have to download SQLite from " https://www.sqlite.org" website & (download Precompiled Binaries for Windows) 
	 to work with SQLite on Windows, you download the command-line shell program. 
	 The downloaded file is ZIP format and its size is quite small. 
	 Extract the content of the file where you want and you should see the sqlite3.exe folder. 
	 To verify the installation, you perform the following steps: 
	 First, open the command line window and navigate to the folder where you unzip your "sqlite3.exe" file. 
	 Second, enter sqlite3, for check the sqlite is working or not. Now type in command prompt "sqlite3 messages.db" for creating a       database.

(5.) open the python script editor and "import from app import db" for importing your "app,py" file to database. And type "db.create_all()" for creating database. 
(6.) Run you Application where your save it "python app.py"
