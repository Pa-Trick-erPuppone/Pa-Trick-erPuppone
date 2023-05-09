- 👋 Hi, I’m @Pa-Trick-erPuppone

- PROGETTO IN COLLABORAZIONE CON JONI GRECA, ANDREA PLESCAN...

<!---
Pa-Trick-erPuppone/Pa-Trick-erPuppone is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

crea un programma usando tkinter e file csv che soddisfano queste richieste:
simula la gestione di un database scolastico avente 3 classi 1A ,1B  1C e i dati di ogni alunno per classe.
fare l'autenticazione differnziato tra alunno e professore, l'alunno inserendo il proprio nome e cognome
puo soltanto vedere il suo account scolastico che contiene nome, cognome voti di alcune materie con la media generale e può vedere le note e compiti che li assegna il professore. 
Mentre se nel login mettiamo le credenziali del professore, essi ha la possibilità di gestire tutti e 3 le classi, puo assegnare compiti alla classe, puo mettere le note ad un singolo alunno, puo visualizzare la lista della classe, ordinarla in base alla media generale e l'insegnante può vedere la pagella di qualunque alunno. Nella pagella mettere la in un cerchio verde se è superiore a 6 altrimenti in un cerchio rosso

# SISTEMA DATABASE SCOLASTICO

Questo è un progetto che piu o meno si occupa della gestione di un database scolastico, con accesso differenziato per alunni e professore. I dati sono sui file JSON quindi non un vero database tipo SQL e come interfaccia utente usiamo semplicemente python.

## Installazione 

come librerie abbiamo usato semplicemente [TKINTER] (https://docs.python.org/3/library/tkinter.html/) per installarlo..

```bash
pip install tkinter
```

## Usare libreria

```python
from tkinter import*
import tkinter.ttk as ttk
# abbiamo usato anche file json
import json 

# per aprire il file json usiamo r che sta per READ
with open('nomeFile.json','r') as f:
    data = json.load(f)
    # load serve per trasformare dati di un file json, in una matrice cosi che possono essere gestiti bene nel file python
```

### Com'è Organizzato 

Il nostro progetto è molto semplice si basa di usare le  classi e funzioni come oggetti che vengono poi richiamati

# Funzionalità

```html
<ul>
    <li>Autenticazione differenziata per alunni e professori</li>
    <li>Visualizzazione dei dati degli alunni, tipo voti,media etc...</li>
    <li>Visualizzazione Generale della classe, Note...</li>
    <li>Aggiornamento automatico dei voti, media se vengono modificati</li>
</ul>
```
# Utilizzo
 
 Per utilizzare il sistema dovete avere: 
 Avere [python] (https://www.python.org/) sul dispositivo
 Un ambiente di sviluppo tipo [VSCode] (https://code.visualstudio.com/) .
 Installare l'estensione di python.
 Installare libreria Tkinter.
 Avviare l'APP
