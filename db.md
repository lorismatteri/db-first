<!-- Istruzioni:
Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

# database name : Negozio di videogames
# nome tabelle: Videogames
- id INT PRIMARYKEY NOTNULL AUTO_INCREMENT UNIQUE
- codice_ean number BINGINT NOTNULL UNIQUE
- titolo string VARCHAR(30) NOTNULL
- descrizione string TEXT NULL
- genere string VARCHAR(15) NOTNULL
- piattaforma string VARCHAR(15) NOTNULL
- pegi_age number TINYINT NOTNULL
- pegi_content string VARCHAR(15) NULL
- anno_di_pubblicazione year NOTNULL
- prezzo number FLOAT(5,2) NULL
- software_house string VARCHAR(30) NOTNULL
- disponibilità number TINYINT NULL DEFAULT(0)
- quantità number SMALLINT NULL DEFAULT(0)
- copie_vendute number SMALLINT NULL DEFAULT(O)
- img_copertina string VARCHAR()NULL
- lingue string VARCHAR(100) NULL
- tema string VARCHAR(50) NULL
- modi_gioco string VARCHAR(15) NULL
- online number TINYINT NULL DEFAULT(O)
- requisiti string VARCHAR(150) NULL
- created_at date DATETIME NOTNULL
- edited_at date DATETIME NULL


