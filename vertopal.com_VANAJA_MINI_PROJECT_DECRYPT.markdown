import random\
import string

chars = \" \" + string.whitespace + string.punctuation + string.digits +
string.ascii_letters chars = list(chars)\
key = chars.copy()

random.shuffle(key)\
print(f\"chars: {chars}\")\
print(f\"key : {key}\")

#DECRYPT\
cipher_text = input(\"Enter a message to encrypt: \")\
plain_text = \"\"

for letter in cipher_text:\
index = key.index(letter)\
plain_text += chars\[index\]

> print(f\"encrypted message: {cipher_text}\")\
> print(f\"original message: {plain_text}\")\
> \# DECRYPT\
> cipher_text = input(\"Enter a message to encrypt: \")\
> plain_text = \"\"
>
> for letter in cipher_text:\
> index = key.index(letter)\
> plain_text += chars\[index\]
>
> print(f\"encrypted message: {cipher_text}\")\
> print(f\"original message: {plain_text}\")

\"C:\\Users\\Vanaja
Asmath\\AppData\\Local\\Programs\\Python\\Python312\\python.exe\"
\"C:\\Users\\Vanaja Asmath\\PycharmProjects\\pythonProject\\vanaja.py\"\
chars: \[\' \', \' \', \'\\t\', \'\\n\', \'\\r\', \'\\x0b\', \'\\x0c\',
\'!\', \'\"\', \'#\', \'\$\', \'%\', \'&\', \"\'\", \'(\', \')\',
\'\*\', \'+\', \',\', \'-\', \'.\', \'/\', \':\', \';\', \'\<\', \'=\',
\'\>\', \'?\', \'@\', \'\[\', \'\\\\\', \'\]\', \'\^\', \'\_\', \'\`\',
\'{\', \'\|\', \'}\', \'\~\', \'0\', \'1\', \'2\', \'3\', \'4\', \'5\',
\'6\', \'7\', \'8\', \'9\', \'a\', \'b\', \'c\', \'d\', \'e\', \'f\',
\'g\', \'h\', \'i\', \'j\', \'k\', \'l\', \'m\', \'n\', \'o\', \'p\',
\'q\', \'r\', \'s\', \'t\', \'u\', \'v\', \'w\', \'x\', \'y\', \'z\',
\'A\', \'B\', \'C\', \'D\', \'E\', \'F\', \'G\', \'H\', \'I\', \'J\',
\'K\', \'L\', \'M\', \'N\', \'O\', \'P\', \'Q\', \'R\', \'S\', \'T\',
\'U\', \'V\', \'W\', \'X\', \'Y\', \'Z\'\]\
key : \[\'z\', \'Z\', \'g\', \'\<\', \'E\', \'L\', \'4\', \"\'\", \'p\',
\'P\', \'9\', \'M\', \'&\', \'\^\', \'8\', \'q\', \'D\', \'3\', \' \',
\'W\', \'k\', \':\', \'\|\', \'V\', \',\', \'F\', \'u\', \'t\', \'}\',
\'m\', \'(\', \'H\', \'R\', \'e\', \'\\x0b\', \'\"\', \'K\', \'C\',
\'!\', \'y\', \'@\', \'\]\', \'1\', \'N\', \'J\', \'c\', \'w\',
\'\\\\\', \'\\n\', \'d\', \'l\', \'X\', \' \', \'\\t\', \'I\', \'\_\',
\'\[\', \'Q\', \'s\', \'j\', \'U\', \'a\', \'x\', \'A\', \'O\', \'\*\',
\'\`\', \'S\', \'.\', \'-\', \'f\', \'B\', \'o\', \'\\r\', \'?\', \'Y\',
\'6\', \'\~\', \'0\', \'%\', \'{\', \'\>\', \'\\x0c\', \'h\', \'r\',
\'=\', \'i\', \'+\', \'7\', \'#\', \'v\', \'/\', \'\$\', \'b\', \'G\',
\'5\', \'T\', \'n\', \')\', \'2\', \';\'\]\
Enter a message to encrypt: I LIKE SURE TRUST\
encrypted message: I LIKE SURE TRUST\
original message: f\
Enter a message to encrypt: I LIKE SURE TRUST\
encrypted message: I LIKE SURE TRUST\
original message: f\
encrypted message: I LIKE SURE TRUST\
original message: f,\
encrypted message: I LIKE SURE TRUST\
original message: f,

encrypted message: I LIKE SURE TRUST

original message: f,\
f\
encrypted message: I LIKE SURE TRUST\
original message: f,\
f\|\
encrypted message: I LIKE SURE TRUST\
original message: f,\
f\|\
encrypted message: I LIKE SURE TRUST\
,\
encrypted message: I LIKE SURE TRUST\
,s\
encrypted message: I LIKE SURE TRUST\
,sl\
encrypted message: I LIKE SURE TRUST\
,sl\^\
encrypted message: I LIKE SURE TRUST\
,sl\^\
encrypted message: I LIKE SURE TRUST\
,\
encrypted message: I LIKE SURE TRUST\
,V\
encrypted message: I LIKE SURE TRUST\
,V\^\
encrypted message: I LIKE SURE TRUST\
,V\^l\
encrypted message: I LIKE SURE TRUST

,V\^ls\
encrypted message: I LIKE SURE TRUST\
,V\^lsV\
encrypted message: I LIKE SURE TRUST\
,V\^lsV,\
Enter a message to encrypt:
