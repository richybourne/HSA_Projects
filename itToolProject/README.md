# IT Internal App Tool

## Description:
	This python script works to display user operating system information without manually having to go 
	find this information. A user will be able to see there IPv4 adress that they can share when working remotely or find the device hostname if the physical asset tag has been lost.
## Usage:
	Within the OUTPUT folder, run the executable and the script should run.

## Notes:
	Do not rename the PY as "systemInfo", this can create a devasting bug.
	No new bugs have been seen.

## Python to EXE Tool	
	$ python -m auto_py_to_exe
	or to include the images
	pyinstaller --onefile --windowed --add-data "Santa_Cruz_County_Seal.ico;." --add-data "Santa_Cruz_County_Seal.png;." myinfoapp.py

<img width="378" alt="Myinfoapp" src="https://user-images.githubusercontent.com/92654141/211412900-69d87072-ce0d-45ee-b018-5f79cdc74987.PNG">
