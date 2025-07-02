![image](https://github.com/user-attachments/assets/09fb938b-03bf-4fb0-aca2-99b2b21024b0)


# Linux: Creating and checking hash values.
This project demonstrates the use of cryptographic hash functions to ensure file integrity and data verification.

# Environments and Technologies Used</h2>
- Google Cloud Virtual Machines.
- Various Linux commands.
- SHA256 hashing algorithm. 

# Operating Systems Used </h2>
- Linux.

# Actions and observations

![image](https://github.com/user-attachments/assets/b3f7ce41-385b-4ba5-937e-42f89e5c8fc6)

- Using the ls command to list files in the directory.

![image](https://github.com/user-attachments/assets/b542aa42-5f43-47fe-a78f-c2973b140ac1)

- Using the cat command to display file contents and seeing that the files are identical.

![image](https://github.com/user-attachments/assets/c2bfc895-4d00-44d3-800c-fdcc359d45d8)

- Using Sha256sum to create hash values for files.

![image](https://github.com/user-attachments/assets/06996438-2394-495e-8875-27ca632aa037)

- Sending both hash value outputs to a file.

![image](https://github.com/user-attachments/assets/77c356e1-b9ea-46ee-819b-e8078a8b4d9b)

- Using the cat command  to display the hash values in the file1hash and file2hash files.

![image](https://github.com/user-attachments/assets/5632820c-9320-4968-8de5-4f9741dfcb8d)

- Using the cmp command to compare the file hashes, the contents of the two files are different because the hash values of each file are different.
