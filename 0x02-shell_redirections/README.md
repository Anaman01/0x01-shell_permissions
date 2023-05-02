echo “Hello, World” -a script that prints “Hello, World”
echo "\"(Ôo)'" - a script that displays a confused smiley
cat /etc/passwd -Display the content of the /etc/passwd file.
cat /etc/passwd /etc/hosts -Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd -Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd -Display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1 -a script that displays the third line of the file iacta.
echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) - a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
ls -la > ls_cwd_content -a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
tail -n 1 iacta >> iacta -a script that duplicates the last line of the file iacta
find . -type f -name "*.js" -delete - a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d -not -name '.' | wc -l - a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted
ls -t1 | head -n 10 - a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldes
sort | uniq -u - a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted
grep -i "root" /etc/passwd - Display lines containing the pattern “root” from the file /etc/passwd
grep -c -i "bin" /etc/passwd - Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -i "root" -A 3 /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
grep -c -i "bin" /etc/passwd - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
grep -i "^[a-z]" /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter
tr "A" "Z" | tr "c" "e" - Replace all characters A and c from input to Z and e respectively.
tr -d "cC" - Create a script that removes all letters c and C from input.
rev - a script that reverse its input.
find . -empty | rev | cut -d '/' -f 1 | rev - 
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f - a script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file
cut -c 1 | paste -s -d '' - a command that finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev - a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep
