pwd-prints the absolute path name of the current working directory.
ls-Display the contents list of your current directory.
cd-changes the working directory to the user’s home directory.
ls -l-Display current directory contents in a long format
ls -la-Display current directory contents, including hidden files
ls -lna-Display current directory contents
mkdir /tmp/my_first_directory-creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory-Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty-Delete the file betty.
rmdir /tmp/my_first_directory-Delete the directory my_first_directory that is in the /tmp directory.
cd - -changes the working directory to the previous one.
file /tmp/iamafile - script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln /bin/ls __ls__ -Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -nu *.html ../ -Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u -moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~ -script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school - creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
