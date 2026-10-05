# TDOR 2026

I file `anno.csv` contengono i dati raccolti da TGEU e riguardano dati a livello mondiale.
Sono scaricabili da: https://tdor.translivesmatter.info/

Nella cartella `NUDM` sono invece presenti i dati raccolti da:
https://osservatorionazionale.nonunadimeno.net/

Questi ultimi sono relativi esclusivamente a casi avvenuti in Italia.

## File disponibili

- `anno.csv`: dati globali raccolti da TGEU
- `NUDM/`: dati italiani raccolti dall'Osservatorio Nazionale
- `mine.ipynb`: notebook Python per interrogare i dati

Il file `mine.ipynb` è liberamente scaricabile e modificabile, così da poter fare ulteriori richieste e analisi.

## Esempio di utilizzo

Nel notebook, il primo blocco di codice stampa nome ed età delle vittime di transfobia in Italia per ciascun anno considerato.

L'output per il 2025 e il 2026 è il seguente:

```text
2025
Giorgio Age:14
Davide Garufo Age:21
Mia Raselli Age:40

2026
Beatrice Age:14
Amelia Caporale Age:about 20
In mine.ipynb sono presenti anche gli anni dal 2020 al 2025. Gli altri anni, come quelli tra 2010 e 2020, possono essere scaricati ed esplorati con la stessa tecnica.
```

Nel secondo blocco di codice, il notebook stampa tutti gli episodi di violenza raccolti da NUDM in cui la vittima non ha genere assegnato alla nascita (F).

Per il 2025 e il 2026, l'output è:

```
2025
{'ID': '1', 'Anno': '2025', 'Data morte': '05/01/2025', 'Regione': 'Campania', 'Provincia': 'Caserta', 'Città': 'Caserta', 'Nome': 'Giorgio', 'Cognome': 'Marziani', 'Note di genere': '(trans)', 'Tipo': [...]}
{'ID': '18', 'Anno': '2025', 'Data morte': '19/03/2025', 'Regione': 'Lombardia', 'Provincia': 'Milano', 'Città': 'Sesto San Giovanni', 'Nome': 'Alexandra', 'Cognome': 'Garufi', 'Note di genere': '(tr[...]'}
{'ID': '65', 'Anno': '2025', 'Data morte': '21/07/2025', 'Regione': 'Lombardia', 'Provincia': 'Bergamo', 'Città': 'Bergamo', 'Nome': 'Thiago', 'Cognome': 'Elar', 'Note di genere': '(trans)', 'Tipo': [...]}
{'ID': '77', 'Anno': '2025', 'Data morte': '15/09/2025', 'Regione': 'Lazio', 'Provincia': 'Latina', 'Città': 'Santi Cosma e Damiano', 'Nome': 'Paolo', 'Cognome': 'Mendico', 'Note di genere': '(M)', [...]}

2026
{'ID': '10', 'Anno': '2026', 'Data morte': '09/02/2026', 'Regione': 'Sicilia', 'Provincia': 'Ragusa', 'Città': 'Vittoria', 'Nome': 'Beatrice', 'Cognome': '', 'Note di genere': '(trans)', 'Tipo': 'sui[...]'}
{'ID': '37', 'Anno': '2026', 'Data morte': '24/06/2026', 'Regione': 'Toscana', 'Provincia': 'Lucca', 'Città': 'Camaiore', 'Nome': 'Mirko', 'Cognome': 'Andreoni', 'Note di genere': '(M)', 'Tipo': 'omi[...]'}
```
Come per il primo esempio, anche in questo caso nel file mine.ipynb sono presenti gli anni dal 2020 al 2025.
