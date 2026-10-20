# Enzopad

Web app per gestire sessioni di D&D in hexcrawl con un Launchpad (Web MIDI).

- Generazione con un click: meteo, incontri, eventi, loot, PNG, voci, rumori, nomi
- Tabelle pesate con rimandi `[[tabella:id]]` e dadi `{2d6+1}`
- Ereditarietà sottoregione → regione → globale
- Tempo, meteo persistente, registro di sessione
- Dati in JSON modificabili dall'interfaccia

## Uso
Apri `index.html` in Chrome o Edge (o servilo con GitHub Pages) e premi "Collega Launchpad".
Supporta Launchpad X, Mini MK3, Pro MK3. Senza hardware usa i pad a schermo.

## Campagne
Puoi tenere più campagne, anche di giochi diversi. Ognuna ha la sua mappa, le sue tabelle, il suo registro e il suo party. Le gestisci dalla scheda "Campagne" del configuratore.

- **Salvataggio automatico nel browser**: ogni modifica resta su questo computer.
- **Collega a un file** (Chrome, Edge): scegli un file `.campagna.json` e da quel momento ogni modifica viene scritta lì. Dopo un riavvio del browser basta un clic su "Riattiva il file". Se il file è più recente della copia nel browser, per esempio perché l'hai usato su un altro computer, viene caricato il file.
- **Apri file…**: riprende una campagna da un file. Se la campagna è già nel browser, viene aggiornata.
- **Scarica**: crea una copia del file da conservare o portare altrove (funziona in ogni browser).

## Giochi diversi
Nella scheda "Gioco e scheda" scegli un modello (D&D old school B/X · OSE, D&D 5e, Il Richiamo di Cthulhu 7e, Mörk Borg, gioco generico) e lo adatti come vuoi:

- risorse con barra (la prima è la principale: PF, Salute, …; le altre possono essere Sanità, Punti magia, Stress…)
- caratteristiche, con il modificatore old school, d20 o percentuale
- statistiche, tiri salvezza, condizioni, valute
- etichette di classe, origine, livello, esperienza, allineamento (vuote = nascoste)
- strumenti old school (tabelle di classe B/X, turni di dungeon e luce, reazione, morale), attivabili a parte

I valori dei personaggi sono salvati per nome: cambiando modello non si perde niente.

## Campagna e party
Il pulsante "Campagna e party" apre il configuratore, diviso in schede:

- **Campagna**: nome, master, ambientazione, date, regole della casa e note segrete
- **Personaggi**: scheda completa con risorse, caratteristiche, statistiche, tiri salvezza, condizioni, poteri, equipaggiamento e monete
- **Seguaci**: mercenari, seguaci e alleati con risorse, morale, paga e padrone
- **Compagnia**: ordine di marcia, turni di guardia, scorte, tesoro comune (e con gli strumenti old school: turni nel dungeon e luce)
- **PNG e fazioni**, **Missioni**
- **Strumenti**: tiro di dadi libero (`1d20+3`, `4d6k3`, `1d100`, `3d6*5`), recupero delle risorse per tutti, distribuzione dell'esperienza; con gli strumenti old school anche iniziativa, reazione e morale. Ogni tiro finisce nel registro della sessione

Nella pagina principale la card "Compagnia" mostra le barre di tutte le risorse con i pulsanti −/+.
