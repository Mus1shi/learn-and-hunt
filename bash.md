## Bash

# Variable

nom="tom"
age=25
 echo "nom : $nom"
 echo "je m'appelle $nom et j'ai $age ans"nom"

 # Condition

 if [ $age -ge 18 ]; then
    echo "Minor"
else
    echo "adult"
fi

# Basic string operation

STRING="this is a string"
SUBSTRING="hat"
expr index "$STRING" "$SUBSTRING"     # 1 is the position of the first 't' in $STRING


STRING="this is a string"
POS=1
LEN=3
echo ${STRING:$POS:$LEN}