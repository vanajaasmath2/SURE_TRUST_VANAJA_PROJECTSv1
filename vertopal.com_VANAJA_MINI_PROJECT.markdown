import random\
import string

chars = \" \" + string.whitespace + string.punctuation + string.digits +
string.ascii_letters chars = list(chars)\
key = chars.copy()

random.shuffle(key)\
print(f\"chars: {chars}\")\
print(f\"key : {key}\")

#ENCRYPT\
plain_text = input(\"Enter a message to encrypt: \")\
cipher_text = \"\"

for letter in plain_text:\
index = chars.index(letter)\
cipher_text += key\[index\]

> print(f\"original message: {plain_text}\")\
> print(f\"encrypted message: {cipher_text}\"

\"C:\\Users\\Vanaja
Asmath\\AppData\\Local\\Programs\\Python\\Python312\\python.exe\"
\"C:\\Users\\Vanaja Asmath\\PycharmProjects\\pythonProject\\vanaja.py\"\
chars: \[\' \', \' \', \'\\t\', \'\\n\', \'\\r\', \'\\x0b\', \'\\x0c\',
\'!\', \'\"\', \'#\', \'\$\', \'%\', \'&\', \"\'\", \'(\', \')\',
\'\*\', \'+\', \',\', \'-\', \'.\', \'/\', \':\', \';\', \'\<\', \'=\',
\'\>\', \'?\', \'@\', \'\[\', \'\\\\\', \'\]\', \'\^\', \'\_\', \'\`\',
\'{\', \'\|\', \'}\', \'\~\', \'0\', \'1\', \'2\', \'3\', \'4\', \'5\',
\'6\', \'7\', \'8\', \'9\', \'a\', \'b\', \'c\', \'d\', \'e\', \'f\',
\'g\', \'h\',

\'i\', \'j\', \'k\', \'l\', \'m\', \'n\', \'o\', \'p\', \'q\', \'r\',
\'s\', \'t\', \'u\', \'v\', \'w\', \'x\', \'y\', \'z\', \'A\', \'B\',
\'C\', \'D\', \'E\', \'F\', \'G\', \'H\', \'I\', \'J\', \'K\', \'L\',
\'M\', \'N\', \'O\', \'P\', \'Q\', \'R\', \'S\', \'T\', \'U\', \'V\',
\'W\', \'X\', \'Y\', \'Z\'\]\
key : \[\'+\', \'1\', \'{\', \'\^\', \'5\', \'Y\', \'b\', \'\`\', \'O\',
\'E\', \'H\', \'S\', \'i\', \'\\t\', \'\~\', \'Z\', \'Q\', \'8\', \'y\',
\'6\', \'L\', \'\>\', \')\', \'B\', \'W\', \'R\', \'/\', \'\]\', \'u\',
\'4\', \'G\', \'\\r\', \'p\', \'z\', \'d\', \'\$\', \'0\', \' \', \'@\',
\'K\', \'r\', \"\'\", \'F\', \'\\x0c\', \'\<\', \'M\', \'q\', \'\_\',
\'\[\', \'e\', \'x\', \'\|\', \'?\', \'\\n\', \'-\', \'=\', \'N\', \'
\', \'v\', \'w\', \',\', \'(\', \'.\', \'X\', \'D\', \'s\', \'\"\',
\'n\', \'7\', \'o\', \':\', \'A\', \'}\', \'\\x0b\', \'C\', \'U\',
\'2\', \'f\', \'k\', \'%\', \'P\', \'!\', \'l\', \'j\', \'9\', \'m\',
\'V\', \'c\', \'t\', \'\*\', \'J\', \'T\', \'h\', \'\\\\\', \'g\',
\'3\', \'a\', \';\', \'&\', \'I\', \'#\'\]\
Enter a message to encrypt: I LIKE SURE TRUST\
original message: I LIKE SURE TRUST\
encrypted message: j\
original message: I LIKE SURE TRUST\
encrypted message: j+\
original message: I LIKE SURE TRUST\
encrypted message: j+V\
original message: I LIKE SURE TRUST\
encrypted message: j+Vj\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h

original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+g\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+gh\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+gh3\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+gh3\\\
original message: I LIKE SURE TRUST\
encrypted message: j+Vjm%+\\3h%+gh3\\g

Process finished with exit code 0
