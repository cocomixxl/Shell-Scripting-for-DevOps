
[Coursera QUILXA25T8F4.pdf](https://github.com/user-attachments/files/18917209/Coursera.QUILXA25T8F4.pdf)
# Shell-Scripting-for-DevOps
# Secure-your-Network-Device

## Objective


### Skills Learned
- Bash (Scripting Language)
- Shell Script
- Linux, Scripting
- Unix Commands, DevOps
- File Management, Unix
- cmd
  
### Tools Used
- CMD
- 
## Steps
### Task 1 - How a script is executable
![image](https://github.com/user-attachments/assets/679e0ad1-a567-4ba4-9ac7-fde085e4d28c)
to make the script executable i need to do the chmod +x filename
![image](https://github.com/user-attachments/assets/737f06a5-63ac-4461-a582-66831fa3a190)

### Task 2 - Passing data to your script
create a variable for future use 
for example username = franco and to call the variable echo $username
![image](https://github.com/user-attachments/assets/1013c750-2419-49ca-8dfa-aa7c9952ebbb)
This is a way to pass data within a script
### Task 3 - Using environment variables
![image](https://github.com/user-attachments/assets/51b5507a-27d5-451c-8b1e-c11b1dc5e8ed)
![image](https://github.com/user-attachments/assets/0029b29b-92df-448e-b57a-a427c7f39db4)
exporting the variable into the global powershell for parent or children
![image](https://github.com/user-attachments/assets/45c54d92-0cd7-4b6c-b382-ef57663eb3fb)
![image](https://github.com/user-attachments/assets/455976dd-94c9-4a92-9d26-f6d98b5d098f)
![image](https://github.com/user-attachments/assets/8c5a6e4c-541a-4620-a1f7-491b418ca925)
![image](https://github.com/user-attachments/assets/ac790e35-666d-4063-8124-7e9960e51b7f)
![image](https://github.com/user-attachments/assets/232717ec-1826-43f7-a654-8bcecbb6c3eb)

### Task 4 - Write a script to backup a directory and relocate it to another location

Write a script that accepts two command line arguments-One for firstname and one for surnome. When run with the two arguments (/myscript Rudi Hinds), the script should print two statements to the command line, utilising the arguments passed into the script:
Hello my first name is Rudi
Hello my surname is Hinds
Your should be able to call your script from the command line with the two arguments and It should work with no errors
![image](https://github.com/user-attachments/assets/3f0b6855-1060-41f8-9fa7-5dd9972a10a1)
make the script exe 
![image](https://github.com/user-attachments/assets/e258010b-e752-44fe-a3a8-3cbe6dc736e6)
![image](https://github.com/user-attachments/assets/de3f1cf1-c0c2-4953-8b11-b04fb82d27fa)
Explanation
$#: Checks the number of arguments passed to the script.

$1 and $2: Represent the first and second command-line arguments, respectively.

The script ensures that exactly two arguments are provided; otherwise, it displays a usage message and exits.

### Task 5 - If Conditionals, the READ and TEST command and Exit codes
![image](https://github.com/user-attachments/assets/90e15957-d95a-4e14-b183-40a5746751a3)
![image](https://github.com/user-attachments/assets/e12303e6-4833-4665-b3a0-056574eb20ec)
create a new directory with some files
![image](https://github.com/user-attachments/assets/dce43d65-c511-4a24-b3ad-7ae7d2981e3a)
![image](https://github.com/user-attachments/assets/4b502934-923e-4f3c-b543-5359ce42e591)
![image](https://github.com/user-attachments/assets/ea23b688-cad7-42d5-8f9a-7dbb61bed5e0)
![image](https://github.com/user-attachments/assets/b4660c78-ca2d-4a15-9ad8-e865f9143f69)
This is a much easier way to sit variables from the users
***
fundimental and important part of scripting cause of the routing inside of a script
![image](https://github.com/user-attachments/assets/368daef5-388f-48b5-9115-0c899a2b1c3d)
3
![image](https://github.com/user-attachments/assets/8e5bd901-61aa-4db6-9f24-f15cadd59d94)
7
![image](https://github.com/user-attachments/assets/08c103e2-5c26-48e3-8165-fb81ebe6a2ce)

![image](https://github.com/user-attachments/assets/36b46fa7-59f6-49bf-b2ab-24fc7c26e729)

![image](https://github.com/user-attachments/assets/04449e34-2a43-4a31-b269-f9fd9fc826b0)



### Task 6 - While, Until, For Loops
For loop
![image](https://github.com/user-attachments/assets/0a3792db-cfb2-4f4f-85ec-cc34e7cacad8)
now for while loops
![image](https://github.com/user-attachments/assets/d6245597-8db8-4818-a237-79814026a94a)
![image](https://github.com/user-attachments/assets/91e518fc-6613-43a5-8ca3-bf442f6e3617)
until
![image](https://github.com/user-attachments/assets/16a5c2b1-7a9b-4d5b-8fc1-5600daf76918)

### Task 7 - Writing our Bash Script

![image](https://github.com/user-attachments/assets/184c2ffb-2382-4d69-a386-e8999762e336)
vim zipandbackup.sh to add the functions
![image](https://github.com/user-attachments/assets/864dfab1-dbc9-4378-b8d2-a2e95dfb47e6)
![image](https://github.com/user-attachments/assets/cbfb38eb-4f5f-45fb-be1d-cb11f37f0fcf)
![image](https://github.com/user-attachments/assets/1410fe48-2e7b-4696-bcc3-b36b02b4b6ce)
success but that's not exactly what we want
![image](https://github.com/user-attachments/assets/8fc4212d-11e3-4064-abd6-8ae455a0d0f2)
so change the exit code in the file

![image](https://github.com/user-attachments/assets/6a594ba2-8f47-4d7b-b5fd-6c2c03b7f938)
now theres a specification 
![image](https://github.com/user-attachments/assets/739ce437-a792-4ff8-8d1f-6eef26a4cb90)


