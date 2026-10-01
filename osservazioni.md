# Osservazioni — Esercitazione 0

Gruppo:

Componenti (nome, cognome e username GitHub di entrambi):

URL del repository condiviso:

Chi ha usato la tastiera nello step 1 e nello step 2:

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:./hello . Abbiamo osservato il messaggio:"Hello, computational physics!"

Che cosa ho capito su sorgente ed eseguibile: La sorgente è il file hello.c su cui si scrive e si apportano le modifiche. L'eseguibile è il file che mi dà l'output richiesto. Se eseguo senza compilare un file con delle modifiche, allora come  output avrò quello dell'ultimo file compilato. 

Output richiesto e comportamento del programma prima della modifica: L'output richiesto era "Hello, computational physics!". Prima della modifica, dato che il main era tutto commentato, non accadeva nulla all'esecuzione del programma.

Esito dopo la modifica e spiegazione della correzione:Dopo la modifica appariva il messaggio richiesto.

## Step 1 — Git

Quali file ho incluso nel commit e perché:output.txt perché contiene l'output del programma

Come ho verificato che la versione provata sia presente su GitHub: Nel mio main di esercitazioni-0-template ho visualizzao il messaggio "Aggiunto output.txt" e il file.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: Argomenti passati: ciao 12 3.5. Comando:./eco ciao 12 3.5. Risultato: ciao 12 3.500000

Che cosa posso concludere: Che i comandi atoi e atof trasformano i comandi rispettivamente in interi e double.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: Argomenti passati: ciao 1 67.5. Comando:./eco2 ciao 1 67.5. Risultato: ciao 1 67.500000 

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: Dato che il programma si aspetta dei caratteri numerici che poi convertirà in interi grazie alla funzione atoi, probabilmente darà una sorta di errore in output.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:Con  echo $ otteniamo a terminale il contenuto del return. Con cat eco.txt visualizziamo ciao 0 3.500000.

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:Basta cambiare gli argomenti

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: Con indicazioni di nomi differenti

Come ho verificato che la versione finale sia presente su GitHub:
