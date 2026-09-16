# Order-to-Cash Process Mining

Repository contenente il codice Python sviluppato per la tesi magistrale:

**“Process Mining e analisi data-driven del processo Order-to-Cash: dalla ricostruzione del processo al modello TO-BE”**

## Contenuto del repository

Il notebook `CODICE_TESI_process_mining.ipynb` contiene le principali elaborazioni utilizzate nella tesi, tra cui:

- importazione e descrizione del dataset OCEL;
- costruzione dell’event log order-centric;
- analisi delle frequenze delle attività;
- calcolo delle frequenze delle relazioni directly-follows;
- Process Discovery mediante Inductive Miner;
- generazione del Process Tree;
- calcolo delle metriche di fitness, precision, generalization e simplicity;
- identificazione e analisi delle varianti di processo;
- calcolo del Cycle Time;
- verifica delle tracce atipiche;
- calcolo degli indicatori temporali:
  - Order-to-Invoice Time;
  - Time-to-Credit-Decision;
  - Return Request Latency;
  - Discount Timing;
  - Invoice-to-Payment Time;
- generazione dei grafici e dei boxplot utilizzati nell’analisi.

## Dataset

Per eseguire il notebook è necessario disporre del file:

`01_o2c.xml`

Il dataset deve essere collocato nella stessa cartella del notebook prima dell’esecuzione.

Il dataset utilizzato è un event log pubblico simulato in formato OCEL 2.0 relativo al processo Order-to-Cash, citato nella tesi come Berti (2024).

## Esecuzione

Il notebook è stato sviluppato in ambiente Python utilizzando principalmente le librerie:

- pandas
- matplotlib
- PM4Py
- Graphviz

Per riprodurre le analisi, aprire il notebook in Jupyter e utilizzare:

`Run → Run All Cells`

## Nota

Il repository è finalizzato alla tracciabilità e alla riproducibilità delle elaborazioni presentate nella tesi.
