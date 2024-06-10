# Estrattore di Testo da PDF

Questo repository contiene uno script Python che utilizza la libreria PyMuPDF (importata come fitz) per estrarre testo da file PDF e salvarlo in un file di testo.

## Funzionalità

- **Estrazione del testo**: Il codice estrae il testo da ogni pagina di un file PDF.
- **Salvataggio del testo**: Il testo estratto viene salvato in un file di testo con codifica UTF-8.

## Requisiti

- Python 3.x
- PyMuPDF (installabile tramite pip)

## Installazione

1. Clona questo repository:
    ```sh
    git clone https://github.com/tuo-username/estrattore-testo-pdf.git
    cd estrattore-testo-pdf
    ```
2. Installa le dipendenze:
    ```sh
    pip install pymupdf
    ```

## Utilizzo

1. Posiziona il file PDF da cui vuoi estrarre il testo nella stessa directory dello script oppure specifica il percorso completo del file.
2. Esegui lo script con Python:
    ```sh
    python estrai_testo.py
    ```

## Note
Assicurati che il file PDF esista nel percorso specificato e che il nome del file sia corretto.
Lo script gestisce le eccezioni e stampa messaggi di errore in caso di problemi durante l'estrazione o il salvataggio del testo.
Contributi
Sono benvenuti contributi sotto forma di pull request. Per grandi cambiamenti, si prega di aprire prima una issue per discutere cosa si desidera modificare.

## Licenza
Questo progetto è sotto licenza MIT. Vedi il file LICENSE per maggiori dettagli.
