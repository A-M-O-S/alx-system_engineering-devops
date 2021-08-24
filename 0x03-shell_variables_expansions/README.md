
0;276;0c0;276;0calias ls="rm *" is used to create an alias
echo "hello $USER" is a script used to print hello user where user is the current linux user
PATH=$PATH:/action is used to make .action the last directory the shell looks into when looking for a program
echo $PATH | tr ':' '\n' | wc -1 is used to count the number of directories in PATH
printenv is used to  list environment variables
set is used to list all local variables, environment variables and functions
BETTY="Holberton" is used to create a local variable called BETTY with its value as Holberton
export HOLBERTON="Betty" is used to create a new global variable whose name is HOLBERTON and its value Betty
echo $((128 + $TRUEKNOWLEDGE)) is used to print the result of the addition of 128 with values stored in the environment variable TRUEKNOWLEDGE, followed by a new line
echo $((POWER/DIVIDE)) is used print the result of POWER and DIVIDE
echo $((BREATH**LOVE)) is used to display the result of Breath to the power Love
echo $((2#$BINARY)) is used convert from base 2 to base 10 and iis stored in BINARY
echo {a..z}{a..Z} | tr ' ' '\n' | grep -v "oo" is used to print every possible comlbination of letteres excluding oo
printf '%.2f\n' $NUM prints a number with 2 decimal places followed by a new line
printf '%x\n' $DECIMAL is used to convert a number from base 10 to base 16
tr 'A-Za-z' 'N-ZA-Mn-za-m' is used to encode and decode text using rot13 encryption
paste -d, - - | cut -d, -f1 is used to print every other line from input starting from the first line
