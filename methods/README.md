# Methods
All'interno di questa cartella sono presenti i metodi utilizzati.

* Dynamic Mode Decomposition (DMD)
* Dynamic Mode Decomposition with Control (DMDc)
* Multi-Resolution Dynamic Mode Decomposition (mrDMD)
* Multi-Resolution Dynamic Mode Decomposition with Control (mrDMDc)

Nei vari codici sono spiegate le istruzioni per la selezione del dataset da voler utilizzare.

Per l'implementazione dell'mrDMDc è stato sostituito il DMD (e la sua ricostruzione) con il DMDc, modificato, della libreria PyDMD. Riguardo le modifiche del metodo sono state aggiunte due variabili di ritorno nella funzione: reconstructed_data(), ovvero eigs e self.modes.
