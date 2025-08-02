# linux-commands

1.  Creating and Renaming Files/Directories
mkdir test_dir (mkdir command to create a directory and using that i have created test_dir folder)
cd test_dir (using cd command to navigate to test_dir folder)
touch example.txt (using touch command to create a file called example.txt)
mv example.txt renamed_example.txt (using mv command to rename a file)

2. Viewing File Contents
cat /etc/passwd (using cat command to view the contents of passwd file)
head -n 5 /etc/passwd (using head command to show the first 5 lines of passwd file)
tail -n 5 /etc/passwd (using tail command to show the last 5 lines of passwd file)

3.Searching for Patterns
grep "root" /etc/passwd (This command shows all the lines containing word "root" in passwd file)

4. Zipping and Unzipping
zip -r test_dir.zip test_dir (This command is used to compress the contents of test_dir folder recursively include all files and subdirectories into a file called test_dir.zip)
unzip test_dir.zip -d unzipped_dir (This command is used to unzip the file and store its contents to a folder called unzipped_dir)

5. Downloading Files
curl https://support.microsoft.com/en-us/office/insert-a-table-of-contents-882e8564-0edb-435e-84b5-1d8552ccf0c0 (It will show the contents of the webpage)
wget https://support.microsoft.com/en-us/office/insert-a-table-of-contents-882e8564-0edb-435e-84b5-1d8552ccf0c0 (It will download the contents of the webpage and store it in a file)

6. Changing Permissions
touch secure.txt
chmod 444 secure.txt

(touch secure.txt → creates an empty file named secure.txt

chmod 444 → sets permissions to:

4 (read) for owner

4 (read) for group

4 (read) for others

This makes the file read-only for everyone.)

7. Working with Environment Variables
export MY_VAR="Hello, Linux!" (export → makes the variable available to child processes. MY_VAR="Hello, Linux!" → assigns the value to the variable)
To verify it's set:
echo "$MY_VAR"
Output - Hello, Linux!





