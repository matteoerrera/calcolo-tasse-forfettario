# Calcolatore Tasse Partita IVA Forfettaria

## Descrizione
Questo progetto è un semplice calcolatore per le tasse della partita IVA forfettaria, realizzato come Single Page Application (SPA) utilizzando HTML, JavaScript e Tailwind CSS.
L'applicazione consente di calcolare:

- **Reddito imponibile lordo**
- **Contributi previdenziali**
- **Reddito imponibile netto**
- **Imposta sostitutiva**
- **Totale dovuto nell'anno**
- **Percentuale del carico fiscale**
- **Netto finale**

## Funzionalità
- **Inserimento compensi annui**: Campo numerico per indicare il reddito atteso.
- **Selezione imposta sostitutiva**: Scelta tra il 5% (per i primi 5 anni) e il 15% (successivamente).
- **Percentuale forfettario**: Campo numerico (default: 67%) con suggerimenti sul codice ATECO.
- **Contributi previdenziali**: Campo numerico (default: 25,98%) con hint per evitare modifiche.
- **Risultati calcolati**: Mostra i dettagli fiscali e il netto rimanente.

## Tecnologie utilizzate
- **HTML5**
- **JavaScript**
- **Tailwind CSS** (caricato tramite CDN)

## Struttura del progetto
Il progetto è contenuto in un unico file HTML con tutto il codice incorporato:
- **Interfaccia grafica**: Utilizza Tailwind CSS per uno stile responsivo e moderno.
- **Logica di calcolo**: Implementata in JavaScript per aggiornamenti dinamici basati sugli input dell'utente.

## Istruzioni per l'uso
1. Scarica il file `calcolatore_tasse.html`.
2. Apri il file in un browser web moderno (es. Chrome, Firefox, Edge).
3. Inserisci i dati richiesti nei campi del calcolatore.
4. Clicca su "Calcola" per visualizzare i risultati.

## Dipendenze
Il progetto utilizza la CDN di Tailwind CSS per gli stili. Assicurati di avere una connessione Internet attiva quando apri il file per caricare gli stili correttamente.

## Note
- Le percentuali di forfettario e contributi previdenziali sono preimpostate sui valori più comuni ma possono essere modificate manualmente.
- La selezione dell'imposta sostitutiva è guidata da un hint per evitare errori.

## Licenza
Questo progetto è distribuito sotto la licenza MIT. Sentiti libero di modificarlo e utilizzarlo come preferisci.
# calcolo-tasse-forfettario
