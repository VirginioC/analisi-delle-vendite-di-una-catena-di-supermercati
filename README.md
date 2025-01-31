# Analisi delle vendite di una catena di supermercati

## Descrizione e obiettivi del progetto
Questo progetto, sviluppato durante il Master in Data Science di Profession AI, consiste nell'utilizzare **Tableau** per costruire una **dashboard interattiva** e una **story** riguardanti le vendite di una catena di supermercati.

L'azienda fittizia Superstore ha deciso di trasformare il proprio processo decisionale adottando un approccio **data-driven**. Per mantenere la propria leadership nel mercato, l'azienda desidera un sistema di monitoraggio continuo delle proprie operazioni in Europa e una strategia marketing mirata sui prodotti con il maggior potenziale di crescita.

Il compito affidato al Data Scientist è creare una soluzione interattiva e dinamica per monitorare le performance aziendali e guidare le scelte strategiche, sostituendo metodi di analisi obsoleti come fogli di calcolo e presentazioni statiche.
Questa soluzione permetterà al business di migliorare l'efficienza, ridurre i costi e aumentare i profitti, assicurando il successo continuo in un mercato altamente competitivo.

## Dataset
Il dataset a disposizione `superstore.csv` è contenuto nel repository ed è costituito da 10000 samples con le seguenti variabili: 

`Row ID`, `Order ID`, `Order Date`, `Dispatch Date`, `Delivery Mode`, `Customer ID`	`Customer Name`, `Segment`, `City`, `State/Province`, `Country/Region`, `Region`, `Product ID`, `Category`, `Sub-Category`, `Product Name`, `Sales`, `Quantity`, `Discount` e `Profit`.

## Dashboard Tableau per il monitoraggio delle attività
Viene creata una **Dashboard Tableau interattiva** che permette al business di monitorare le seguenti metriche chiave tramite grafici:

- **Andamento delle vendite nel tempo**
- **Profitto per Stato**
- **Quantità di prodotti spediti per classe di spedizione**
- **Categorie di prodotto più vendute**

I grafici possono essere filtrati per `Delivery Mode`, `Category`, `Country`, `Year` e `Month`.

## Tableau Story per la strategia di allocazione del budget marketing
Superstore ha a disposizione un budget marketing significativo per promuovere i prodotti ad alto potenziale. Il business richiede un’analisi che supporti la decisione di allocazione del budget e a tal proposito viene costruita una **Tableau Story** costituita da 6 story point contenenti delle dashboard:

1. **Panoramica dell'attuale performance di Superstore in Europa**: contiene la dashboard di monitoraggio precedentemente creata.
2. **Analisi dei profitti e delle quantità di prodotti venduti per categoria e sottocategoria**: è inserito nella dashboard anche il profitto per stato e i grafici possono essere filtrati per `Category`, `Sub-Category` e `Country` in modo da esplorare le variazioni di profitto e quantità in dettaglio.
3. **Prodotti da rimuovere**: vengono individuate le sottocategorie di prodotti che portano a delle perdite andando poi ad individuare singolarmente i prodotti da rimuovere.
4. **Prodotti a cui assegnare più budget**: vengono individuate le sottocategorie di prodotti che hanno un alto margine di profitto confrontando i profitti e le quantità vendute.
5. **Prodotti a cui assegnare meno budget**: vengono individuate le sottocategorie di prodotti che hanno un basso margine di profitto confrontando i profitti e le quantità vendute.
6. **Conclusioni**: in conclusione vengono sintetizzati in un'unica dashboard tutti i risultati a cui si è giunti.

## Come visualizzare la Dashboard e la Story
1. Visualizza la Tableau story con tutte le dashboard e i singoli charts che le compongono su **Tableau Public** cliccando sul link https://public.tableau.com/app/profile/virginio.cocciaglia/viz/SuperstoreSalesOverviewandBudgetAllocationStrategies/Story.
2. In alternativa scarica o clona il repository ed apri il file `Superstore Sales Overview and Budget Allocation Strategies.twbx` su **Tableau Desktop**. Questo file contiene già il dataset `superstore.csv`, quindi non sono necessarie configurazioni aggiuntive.











