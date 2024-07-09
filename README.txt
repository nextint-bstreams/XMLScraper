ESECUZIONE

Premessa: i nomi dei file e dei parametri devono essere case sensitive.

1) Sotto "Source", creare una sottocartella con esattamente lo stesso nome dei file Html (per. es. se i file si chiamano "A1_2024_PANORAMA-n.html, la cartella dovrà chiamarsi "A1_2024_PANORAMA").

2) Copiare il file .xml dentro la cartella appena creata, e rinominarla nello stesso modo della cartalla (es. A1_2024_PANORAMA.xml)

3) Copiare i file HTML del volantino (A1_2024_PANORAMA-1.html, A1_2024_PANORAMA-2, ...) dentro la stessa cartella

4) da prompt di DOS, lanciare il comando "xmlscraper.exe NOMEPROGETTO" (per es. "idmlscraper.exe A1_2024_PANORAMA")

5) Al termine dell'esecuzione dello script, verranno generati due file nella cartella "Output":
   - NOMEPROGETTO.csv (per es. "A1_2024_PANORAMA.csv") popolato con i dati presenti nel file xml di indesign
   - NOMEPROGETTO_UrlPagina.csv (per es. "A1_2024_PANORAMA_UrlPagina.csv") con le url delle pagine html corrispondenti ad ogni pagina del volantino
