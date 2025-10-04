# Gestione di Serie Temporali con TimescaleDB: un’analisi sperimentale
Nell’attuale contesto della raccolta e gestione di grandi volumi di dati temporali, le
serie temporali assumono un ruolo cruciale in numerosi ambiti applicativi, dall’Internet
of Things al monitoraggio ambientale, dai sistemi industriali ai servizi digitali. Tuttavia,
le peculiarità di questo tipo di dati, ad alta frequenza di registrazione e rapida crescita nel
volume, pongono sfide significative in termini di scalabilità, efficienza delle interrogazioni
e persistenza nel lungo periodo.

Questa Tesi esplora le potenzialità di TimescaleDB, un’estensione per PostgreSQL
progettata specificamente per la gestione efficiente delle serie temporali, confrontandola
con soluzioni alternative tradizionali e specializzate. Viene approfondita l’architettura di
TimescaleDB, evidenziando le sue soluzioni innovative come l’approccio ibrido tra data-
base relazionali e soluzioni pensate ad-hoc per le time-series, come l’uso di hypertable e
chunking automatico, nonché le ottimizzazioni per query aggregate e compressione dei
dati.

Attraverso un caso di studio basato su dati raccolti da un sensore reale, viene simu-
lata la strutturazione di un’applicazione concreta di gestione di serie temporali. Questo
scenario funge da riferimento pratico per introdurre le problematiche tipiche del domi-
nio. I test prestazionali veri e propri, invece, vengono condotti separatamente su dati
generati artificialmente, in scenari controllati, al fine di analizzare in modo sistematico le
performance del sistema in termini di scalabilità, tempi di risposta, efficienza delle
query e capacità di compressione. I risultati evidenziano l’efficienza complessiva di
TimescaleDB nell’elaborazione e compressione di grandi volumi di dati temporali, anche
in scenari ad elevato carico.

L’obiettivo è comprendere vantaggi, limiti e implicazioni pratiche dell’adozione di una
soluzione come TimescaleDB nella gestione di time series a lungo termine. Infine, vengo-
no presentate alcune considerazioni conclusive e possibili sviluppi futuri, con particolare
attenzione all’evoluzione delle tecnologie per la gestione di dati temporali su larga scala.
