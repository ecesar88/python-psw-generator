# *python-psw-generator*
## A simple python program to generate passwords

### Usage:
```
$ python psw-generator-2.0.3.py
usage: psw-generator-2.0.3.py [options]
psw-generator: A simple python program to generate passwords

optional arguments:
  	-h, --help      Show this help message and exit
  	-r REPEAT       Repeat: Number of passwords to be generated at a time
  					(default=1 password)
  	-l LENGTH       Length: The lenght of the password to be generated
					(default=25 chars long)
 	-t {1,2,3,4,5}  Type: The type of the password to be generated (default= 5).
                    Possible types are:                                  
                       1 - UPPERCASE ONLY                                     
                       2 - lowercase only                                     
                       3 - 1234567890 only                                    
                       4 - !@#$%¨&* only                                      
                       5 - Mixed 12ab!@
  -v              Version: Show the program's version and exit.
  ```