Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.

Colonne | Tipo | Attributi
--- | --- | ---
id | BIGINT | PRIMARY_KEY  AUTO_INCREMENT
Marca | VARCHAR | NOTNULL
Modello | VARCHAR | NOTNULL
Prezzo | INT | NOTNULL
Prezzo_originale | INT | NULL
km | INT | NOTNULL
Anni | SMALL | NOTNULL
Alimentazione | VARCHAR | NOTNULL
Colore | VARCHAR | NOTNULL
Porte | TINYINT | NOTNULL DEFAULT('3')
Cambio | CHAR(1) | NOTNULL DEFAULT('m')
Stato | CHAR(1) | NULL

