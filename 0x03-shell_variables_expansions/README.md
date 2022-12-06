alias ls="rm *" -  a script that creates an alias.

Name: ls
Value: rm *
echo "hello $USER" - a script that prints hello user, where user is the current Linux user.
export PATH=$PATH:/action - Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) - a script that counts the number of directories in the PATH.
printenv -  a script that lists environment variables.
set - a script that lists all local variables and environment variables, and functions.
BEST="School" - a script that lists all local variables and environment variables, and functions
export BEST="School" -  a script that creates a new global variable.

Name: BEST
Value: School
echo -e $((128 + TRUEKNOWLEDGE)) -  a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER / $DIVIDE)) - a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables
echo $(($BREATH**$LOVE)) - a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line
echo $((2#$BINARY)) - a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line
echo {a..z}{a..z} | tr " " "\n" | grep -  a script that prints all possible combinations of two letters, except oo.

Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" -  a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.
printf "%.2f" $NUM | sort - a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable DECIMAL
The script should display the number in base 16, followed by a new line

