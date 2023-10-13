# Betfair Historical Data Parser

## Installing Python
1) Download and install Python<br/>
	32-bit Windows:<br/>
	https://www.python.org/ftp/python/3.11.0/python-3.11.0.exe<br/>
	
	64-bit Windows:<br/>
	https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe<br/>
	
	**Make sure to check the "Add python.exe to PATH" at the bottom of the installation window.**<br/>
	![image](https://drive.google.com/uc?export=view&id=1CqbfL0qezreCyh4GvQTOmwwILhPlwWnO)

## Installing the requirements
Open a command prompt and navigate to the script's directory.<br/> 
The easiest way is to open the script's folder and type cmd in the address bar.
![image](https://drive.google.com/uc?export=view&id=1RA6M-eZckbJqzI7vFIqpaNE-WVbO0feH)
<br/>
Type the following command, you have to do this only once:<br/>
```
pip install -r requirements.txt
```

## Starting the script
The script will read all TAR files from the InputFolder and write the CSV files to the OutputFolder - one CSV file per TAR file.<br/>
You can start the script with the following command: <br/>
```
python main.py
```
