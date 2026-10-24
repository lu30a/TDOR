# TDOR 2026

I file `anno.csv` contengono i dati raccolti da TGEU e riguardano episodi a livello mondiale.
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

Nel notebook, il primo blocco di codice stampa nome ed età delle vittime di transfobia in Italia raccolti da TGEU per ciascun anno considerato.

L'output per il 2025 e il 2026 è il seguente:

```text
2025
Giorgio Age:14
Davide Garufo Age:21
Mia Raselli Age:40
--------------------
2026
Beatrice Age:14
Amelia Caporale Age:about 20
```
In mine.ipynb sono presenti anche gli anni dal 2020 al 2025. Gli altri anni, come quelli tra 2010 e 2020, potrebbero essere scaricati ed esplorati con la stessa tecnica.

Nel secondo blocco di codice, il notebook stampa tutti gli episodi di violenza raccolti da NUDM in cui la vittima non ha genere assegnato alla nascita (F).

Per il 2025 e il 2026, l'output è:

```
2025
Giorgio Marziani Age:14
Alexandra Garufi Age:21
Thiago Elar Age:27
Paolo Mendico Age:15
--------------------
2026
Beatrice  Age:14
Mirko Andreoni Age:24
```
Come per il primo esempio, anche in questo caso nel file mine.ipynb sono presenti gli anni dal 2020 al 2025.
