# The Orienteering Problem
## Risoluzione tramite algoritmo genetico
### Repository per il progetto d'esame di Algoritmi di Ottimizzazione Combinatoria e su Rete (UNINA)

Lo scopo del progetto consiste nell'implementare un **algoritmo genetico** adatto a risolvere il **problema di orienteering** (OP), nella fattispecie il lavoro si è concentrato sulla variante del problema con starting point differente dall'ending point (_OP with Mandatory Visits_) e l'algoritmo è stato realizzato sfruttando la libreria **DEAP**. Le soluzioni ottenute vengono poi confrontate con quelle ottime fornite dall'algoritmo esatto, implementato tramite la libreria _Gurobi_ come problema di PLI, con formulazione MTZ per i subtour elimination constraints. I risultati ottenuti sono esposti all'interno della documentazione fornita (_OP_GA_vs_MTZ_); il codice dell'algoritmo genetico e dell'algoritmo esatto si trovano rispettivamente nelle cartelle _op_ga_ e _op_mtz_.
