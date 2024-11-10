**Typical structure:**
	Open file
		file_variable = open("filepath", "r or w for read or write")
			If there is no file with that name it will create on in the current dir
	Process
		Read (see below for read methods)
		Write print("text for file" file =file-variable)
	Close file
		file_variable.close()

**Reading Files:**
	readlines()
		returns a list of strings
	readline()
		reads a single line
	read()
		read the entire file as a string

**Writing to files:**
	print(text , file="filepath" or file_variable)

**File related methods from os.py:**
	import os
	os.getcwd()
		Returns the filepath for the working directory(folder) that you are in
	os.listdir()
		Returns a list of the names of the files and subfolders in the current directory
	os.chdir("filepath/name") or ("..")
		changes the current directory. ".." Goes up a folder in the directory
	
