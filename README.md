# Metodi data-driven e tecniche multi-resolution per l’identificazione di processi industriali
L'obiettivo di questo elaborato di tesi è l'implementazione di un metodo data-driven in grado di identificare un processo industriale dinamico e non lineare a partire da dati sperimentali. Il metodo in questione è il Multi-Resolution Dynamic Mode Decomposition with Control (mrDMDc).
All'interno di questa repository troverete tutto l'occorrente per replicare i risultati ottenuti e i vari errori riscontrati durante l'implementazione.

Tutti i metodi sono stati implementati su Jupyter Notebook.

Per prima cosa consiglio di scaricare tutti i dataset utilizzati in modo da poter sceglierli con più facilità direttamente all'interno del codice spuntando i vari cancelletti (#).
L'errore riscontrato nell'implementazione riguarda la funzione "stitch" all'interno del metodo mrDMDc. In particolare, l'errore specifico è: ValueError: shapes (40,7) and (0,7160) not aligned: 7 (dim 1) != 0 (dim 0). 
