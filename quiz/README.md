﻿Quiz
===
CSV File must have for the first row the following field
we should use all ascci character, for particuale char use the html encoding;

- question	: The question that will be presented
- correct_answer	: The correct answer
- id (optional)	: an unique identificative of the question
- wrong_answer (optional)	: If this filed is present this anwer will be forced to be one on the option in the answer (diffrent   answer are separated by |
- difficult_level (optional)(int)	 : Number that identify the difficulties of the question (0 easiest 100 hardest)
- response_type (optional)	: options -> multiple options ; not_null -> anything not null; int -> integer

#TODO
##V 1.0
- implementare: response_type  not_null, int
- eliminare l'import delle righe vuote dal csv
- verificare per i caratteri non ascii non codicifati con &egrave; ... ma con &#444

##v1.1 
- aggiungere tempo di questionario
- export in PDF
- possibilità di invertire domande con risposte (e anche solo qualche domanda con qualche risposta) dallo stesso csv

##v2.0
- inserire la memorizzazione delle risposte giuste in modo da chiedere solo quelle che non si sanno
- inserire template 

#DONE
- Possibility to implement specific configuration from XML file