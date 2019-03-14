# Simulazione verifica Informatica: Processing
Simulazione della verifica di laboratorio con Processing su classi, metodi e oggetti 3D.
Classe: 2Binf, a.s. 2018/2019

Nella cartella `design` trovate le istruzioni per l'applicazione che dovrete implementare.

## Esecuzione del compito
Eseguite le seguenti operazioni:

- [ ] accedete con il vostro account personale a GitHub (**non sbagliate password!** altrimenti bloccate l'accesso a tutta la classe)
- [ ] fate il fork di questo progetto, premendo il tasto con la forchetta che si trova in alto a destra nella pagina
- [ ] deve comparire un libro infilzato da una forchetta sopra uno scanner, aspettate che finisca
- [ ] controllate che l'URL contenga il **vostro** nickname (e non il mio)
- [ ] scaricate il progetto premendo sul tastone verde a destra "Clone or Download" e quindi "Download zip"
- [ ] con Processing, aprite il file `code.pde` all'interno della cartella code
- [ ] implementate il progetto

Quando avete finito e **comunque 5 minuti prima** dello scadere del tempo (vi verrà ricordato dal docente), dovete pubblicare il codice seguendo la procedura:
- [ ] sul browser, nella pagina del **vostro** repository, andate su `code/code.pde`, quindi sulla matita
- [ ] copiate e incollate il progetto che avete fatto sul vostro computer sul browser
- [ ] dopo aver incollato, in basso premere su "Commit changes"
- [ ] per confermare la consegna del compito, tornate sul mio repository originale, andate su "Issues" e rispondete alla mia issue con il testo "Nome Cognome, consegnato"


# Calcolo del punteggio
Punti generali:
- [ ] corretta indentazione del codice
- [ ] codice che compila
- [ ] chiarezza del codice (commenti, identificativi, etc.)

Punti progetto:
- [ ] creare una classe `Personaggio`
- [ ] dichiarare una variabile di tipo `Personaggio`
- [ ] assegnare alla variabile creata il modello `hermione.obj`
- [ ] colorare il personaggio creato in accordo con il design
- [ ] creare un metodo nella classe Personaggio per disegnarlo
- [ ] disegnare il personaggio
- [ ] far muovere il personaggio in accordo con il design
- [ ] analogamente a quanto fatto finora, creare una classe `Trasfigurabile` con un metodo per disegnarlo
- [ ] creare una variabile di tipo `Trasfigurabile` per la piuma e disegnare la piuma
- [ ] far muovere la piuma e fermarla quando arriva vicino a Hermione __(fino a qui per la sufficienza)__

- [ ] aggiungere due variabili di classe `x` e `y` di tipo `float` alla classe `Trasfigurabile`
- [ ] aggiungere anche un metodo `sposta()` per variare i valori di posizione
- [ ] aggiungere il metodo `trasfigura()` alla classe `Trasfigurabile`, che modifica il valore alpha dell'oggetto
- [ ] nella stessa posizione della piuma, disegnare il colibrì, anch'esso deve essere della classe `Trasfigurabile`
- [ ] il valore iniziale di alpha del colibrì deve essere 0 (completamente trasparente)
- [ ] quando si preme la barra spaziatrice, fare in modo che lentamente la piuma svanisca e appaia il colibrì
- [ ] fare in modo che la somma dei valori di alpha del colibrì e della piuma sia sempre 255

Totale punti (generali+progetto): 20

Sufficienza: 11

Per avere il massimo del voto bisogna avere il massimo del punteggio.


# Note generali
Eseguite spesso la vostra applicazione per essere sicuri di procedere correttamente

**È possibile** consultare Internet o dal [progetto di esempio](https://github.com/marconicivitavecchia-story/cappuccetto-rosso) del professore durante la verifica.

Al contrario, **non è possibile** comunicare o copiare dai compagni di classe.
