# Configuratore Privati Winnerdoor e WinnerLite 1.0.15

Il Configuratore Privati comprende Winnerdoor e WinnerLite nello stesso programma Windows e nella stessa applicazione online. All'avvio si sceglie il prodotto, poi una preconfigurazione di catalogo oppure una nuova configurazione. Il riferimento cliente è obbligatorio prima dell'esportazione PDF.

## Novità della 1.0.15

Riconciliate tutte le **106 voci WinnerLite** con il [catalogo pubblico 2026-2027](https://www.winnerdoor.it/porte-ingresso-catalogo-lite), comprese le **78 tavole descrittive**: **88 preconfigurazioni complete** e **18 schede di sola consultazione**. Le 16 voci senza distinta nella brochure WinnerLite impiegano una dotazione proposta dal corrispondente modello Winnerdoor, con componenti verificati nelle tabelle WinnerLite. Le informazioni della scheda indicano separatamente pagine della brochure, fonte della proposta e differenze.

Corrette quattro miniature e i relativi riferimenti: **L25344, L20160, L16029 e L16007**. L25344 segue la propria scheda descrittiva, pagina 12 del catalogo (PDF 14); L20160 rimanda a pagina 25 (PDF 27), L16029 alla posizione corretta nella stessa pagina e L16007 all'indice (PDF 10). Il collegamento al catalogo WinnerLite apre una nuova scheda e conserva la configurazione in corso.

Le regole di calcolo, i limiti dimensionali, le compatibilità e l'ordine dei layer restano quelli esistenti. Il catalogo Winnerdoor conserva **178 schede: 171 complete e 7 non disponibili alla base standard**. Il pomolo **D70140** rimane disponibile per L20181/L25182 e riportato nel riepilogo e nel PDF: il suo layer esterno è ancora da fornire e l'avviso relativo resta visibile.

## Download e accesso online

- [Centro download Winnerdoor](https://www.winnerdoor.it/test-page)
- [Configuratore online](https://configurators.web-bay.com/)
- [Release 1.0.15](https://github.com/Mixall-Group/winnerdoor-configuratori-download/releases/tag/winnerdoor-privati-v1.0.15)
- [Installer Windows x64](https://github.com/Mixall-Group/winnerdoor-configuratori-download/releases/download/winnerdoor-privati-v1.0.15/Winnerdoor-Setup-1.0.15.exe)
- [ZIP portabile](https://github.com/Mixall-Group/winnerdoor-configuratori-download/releases/download/winnerdoor-privati-v1.0.15/Winnerdoor-Privati-1.0.15-portabile.zip)

La consegna comprende installer, ZIP, GUIDA_PRIVATI.txt e SHA256SUMS.txt. Sorgenti e materiali aziendali restano privati. Installer e ZIP sono stati verificati rispetto alla distinta locale, compresi dimensioni, impronte SHA-256 e contenuti dell'archivio.

## Installazione e aggiornamenti

L'installazione interattiva chiede la cartella di destinazione. Per una copia già installata, dopo l'attivazione del rilascio, **Aggiorna ora** scarica l'installer verificato e aggiorna nella cartella esistente senza disinstallazione manuale. Dalla 1.0.11 un aggiornamento verificato è obbligatorio; il lavoro aperto viene conservato e può essere recuperato con **Riapri ultima bozza**.

Per la versione portabile occorre estrarre tutti i file del nuovo ZIP. Bozze e impostazioni restano nel profilo Windows del computer e non seguono automaticamente la chiavetta. Non occorre creare un account GitHub né installare Git o Rust.

La versione online si aggiorna alla riapertura della pagina; se una configurazione è già aperta, salvare la bozza e ricaricare dall'avviso di nuova versione. Le immagini remote richiedono Internet. L'elaborazione della configurazione usa il motore locale; l'attuale distribuzione non comprende un archivio completo di immagini offline.

Le immagini continuano a usare Imgur e le origini attuali. Il nuovo archivio viene mantenuto aggiornato e i configuratori legacy Winnerdoor/WinnerLite restano attivi e aggiornati in parallelo fino alla dismissione concordata.

## Controlli del rilascio

Superati **337 test**, cinque fixture esplicite escluse come previsto ed eseguito separatamente il controllo PDF WinnerLite. Formato e Clippy Windows su tutti i target e binari WebAssembly senza avvisi. Verificati 444 file della consegna, 440 portabili e CRC/contenuti del ZIP.

Il PDF continua a riutilizzare le viste già acquisite. Il campione WinnerLite con **28 voci e due viste** è stato verificato su **una pagina A4**, con Arial incorporato, titoli in grassetto, valori regolari e nessun taglio o distorsione. Nel confronto di 50 file del nucleo e dei dati è cambiato soltanto il registro delle preconfigurazioni WinnerLite.

La conferma dell'utilizzatore sull'installazione sul secondo PC e sulla tastiera di telefono/tablet ricevuta il 26 novembre riguarda la **1.0.14**; resta distinta dai controlli della 1.0.15. L'attivazione dell'aggiornamento 1.0.15 segue la pubblicazione della pagina Webflow e la verifica dei due download pubblici.
