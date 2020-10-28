# Programmi in Python per il corso di "Machine Learning con Applicazioni".
I programmi in questa repository sono parte integrante del suddetto Dipartimento di Fisica dell'Univestità degli Studi di Milano.
I Python notebooks in questa repository sono in gran parte dovuti al Prof. M. Hjorth-Jensen e derivano dagli esempi usati per l'omonimo corso all'università di Oslo. Tutti file qui presenti sono stati adattati da C. Barbieri per il **primo semestre, a.a. 2020/21**.

La componente computazionale del corso usa *python 3.x* e fogli note (notebooks) di *jupyter*. I notebook in ogni cartella approfondiscono un particolare argomento trattato a lezione.
Siccome non sarà possibile accedere fisicamente al laboratorio di calcolo per le lezioni, i notebook verrnno descritti e spiegati durante le normali lezioni (telematiche). 


Per accedere alla repository: [https://gitlab.com/craolus/MachineLearning-con-applicazioni.git](https://gitlab.com/craolus/MachineLearning-con-applicazioni.git). (**NB:** I juputer notebook possono anche essere scaricati direttamente dal sito usando l'icona a destra vicino a 'clone'.)


## Come aggiornare la copia locale della repository
Man mano che il nuovo materiale viene aggiunto durante il semestre, si può aggiornare la copia locale della repository come segue (se già clonata come descritto più avanti):

```bash
$ cd MachineLearning-con-applicazioni
$ git pull
```
È bene ricordarsi di **cambiare il nome dei file di notebook** su cui si sta lavorando, per non sovrascriverne il contenuto.


## Primi Passi
Aprire un terminale e muoversi nella cartella in cui si intende lavorare (`cd` in unix/linux):
```bash
$ cd My_folder
```
Dai computer del *Laboratorio di Calcolo* in dipartimento, è necessario attivare l'istallazione di anaconda 
```bash
$ module load python3/anaconda
```
Sul proprio computer, conviene controllare che Anaconda e python siano presenti 
```bash
$ which python
/home/username/anaconda3/bin/python
```
Per clonare la repository usare uno dei seguenti comandi:
```bash
$ git clone https://gitlab.com/craolus/MachineLearning-con-applicazioni.git
oppure
$ git clone git@gitlab.com:craolus/MachineLearning-con-applicazioni.git
```
Questo crea una cartella `MachineLearning-con-applicazioni` (N.B.: la seconda opzione, via ssh, può richiedere un account su GitLab ed una public key. Se da errori, usare `https` invece). Una volta entrati nella caterlla, jupiter viene invocato digitando `jupyter lab` da terminale:
```bash
$ cd MachineLearning-con-applicazioni
$ jupyter lab
```
Questo apre una nuova tavola nel browser all'indirizzo `localhost:8888`. Cliccando sulla cartella `Esempi1-Introduzione` e poi su `PythonIntro_FunzioniPerRegrLin.ipynb`, si è pronti ad iniziare!


## Istallare jupyter sul proprio computer
Risovere gli esercizi richiede una versione recente di `python`, che includa `jupyter`, `numpy`, `matplotlib` e alcune altre librerie standard in python. Se queste non sono presenti, la soluzione migliore per evitare di interferire con eventuali python già presenti nel sistema operativo è quella di istallare [Anaconda](https://www.anaconda.com/download/), la quale mantiene una distribuszione completa e aggiornata di python e relativi strumenti per vari sistemi operativi.  Dal sito qui sopra scegliere **python 3.x** ed il proprio OS per scaricare ed istallare il tutto. 


## Ricerca di esempi in rete
In certe situazioni può diventare utile ed efficiente **riadattare codici altrui** o prenderne esempio (purché la paternità del codice venga propriamente riconosciuta!). Nel risolvere questi esercizi, *non* è richiesto rifare tutto da capo, cercare informazioni in reter su *how to do X in python* è ammesso. Alcuni siti che riportano informazioni utili sono:

+ Un buon forum dove cercare informazioni di natura computazionale:
  + [Stackoverflow](https://stackoverflow.com/)

+ Documentazioni ufficiali:
  + [Numpy documentation](https://docs.scipy.org/doc/numpy/reference/routines.html)
  + [Scipy documentation](https://docs.scipy.org/doc/scipy/reference/)
  + [Jupyter Lab documentation](https://jupyterlab.readthedocs.io/en/stable/)

+ Tutorial per Pyhon:
  + [Data Flair Python Tutorials](https://data-flair.training/blogs/python-tutorials-home/)
  
## Ricevimento
Gli studenti in necessità di aiuto o chiarimenti sono vivamente invitati a contattare il docente  `carlo.barbieri@unimi.it` oppure a connettersi in via telematica durante l'ora di ricevimento (martedì 14:00-15:00, info su Ariel). Per orari diversi mandate una mail in anticipo.


C. Barbieri,  ottobre 2020.
