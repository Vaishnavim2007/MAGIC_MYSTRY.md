# **MISC**
## MAGIC_MYSTRY 
METHODS: <br/>
•	The flag is within the chall.png file, which is initially inaccessible <br/>
•	By using  the terminal command hexdump -C chall.png | less we generate the hexdump of the chall.png file <br/> 
•	Compare the generated hexdump with that of a known PNG file to identify discrepancies <br/> 
•	Identify the differences in the first line of the hexdump <br/> 
•	The flag is inside the file chall.png which we cannot access initially <br/> 
•	Using ghex we  modify the hexdump, correcting the differences and saving the revised file <br/> 
•	We then Open the newly created file to reveal the hidden flag <br/>
WHAT I LEARNT: <br/> 
•	I learned about the internal structure of PNG files, including their headers and how data is organized  <br/>
•	Also how files are represented in hexadecimal and how changes in the hexadecimal data affect the file’s functions  <br/> 
•	learned how to use a hex editor to modify the hexadecimal representation of a file  
