## Esercizio di oggi: DB First
### nome repo: db-first

- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.


# Creare una tabella

Id  | TARGA | MARCA | MODELLO | TIPO CARBURANTE | COLORE | CONDIZIONE | NUMERO PROPRIETARI | KILOMETRAGGIO | PREZZO D'ACQUISTO| PREZZO VENDITA | ANNO IMMATRICOLAZIONE | ANNO FABBRICAZIONE | DESCRIZIONE
---|---|---|---|---|---|---|---|---|---|---|---|---|
 TIPO|
|BIGINT|VARCHAR(8)|VARCHAR|TINYINT|VARCHAR|VARCHAR|TINYINT|TINYINT|MEDIUMINT|MEDIUMINT|MEDIUMINT|YEAR|YEAR|TEXT
ATTRIBUTI|
PRIMARY_KEY,AUTOINCREMENT|NOTNULL,UNIQUE|


