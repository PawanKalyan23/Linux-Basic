# Linux-Basic
Assignment for linux basic creation and deletion of files and folders

ASSIGNMENT 1:

Create a directory named test_dir using mkdir: mkdir test_dir
Inside test_dir, create an empty file called example.txt: touch example.txt
Rename example.txt to renamed_example.txt using mv: mv example.txt renamed_example.txt

<img width="1920" height="1200" alt="Screenshot 2026-03-17 202144" src="https://github.com/user-attachments/assets/06056b18-c138-4122-a9c0-b11a16474161" />


ASSIGNMENT 2:

Use cat to display the contents of /etc/passwd: cat /etc/passwd
Display only the first 5 lines of /etc/passwd using head: head -n 5 /etc/passwd
Display only the last 5 lines of /etc/passwd using tail: tail -n 5 /etc/passwd

ASSIGNMENT 3:

Use grep to find all lines containing the word "root" in /etc/passwd: grep “root” /etc/passwd

ASSIGNMENT 4:

Compress the test_dir directory into a file named test_dir.zip using zip: zip -r test_dir.zip test_dir
Unzip test_dir.zip into a new directory named unzipped_dir: unzip test_dir.zip -d unzipped_dir

ASSIGNMENT 5:

Use wget to download a file from a URL (e.g., https://example.com/sample.txt): wget -b https://example.com/sample.txt

ASSIGNMENT 6:

Create a file named secure.txt and change its permissions to read-only for everyone using chmod: touch secure.txt , chmod 444 secure.txt

ASSIGNMENT 7:

Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!": export MY_VAR=”Hello, Linux!” , echo $MY_VAR
