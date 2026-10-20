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

## Campagna e party
Il pulsante "Campagna e party" apre il configuratore, diviso in schede:

- **Campagna**: nome, regolamento, master, ambientazione, date, regole della tavola (PX per tesoro, soglia di morte, iniziativa, ingombro), regole della casa e note segrete
- **Personaggi**: scheda completa old school (caratteristiche con modificatori, PF, CA, THAC0, tiri salvezza, PX con bonus del requisito primario e soglia del livello successivo, condizioni, incantesimi, equipaggiamento, monete). Tiri 3d6 in ordine, tiro dei PF e valori di classe B/X automatici
- **Seguaci**: mercenari e seguaci con PF, morale, paga e padrone
- **Compagnia**: ordine di marcia, turni di guardia, turni nel dungeon, luce, scorte, tesoro comune
- **PNG e fazioni**, **Missioni**
- **Strumenti**: distribuzione dei PX (mezza quota ai seguaci), riposo, iniziativa, reazione e morale, con il risultato scritto nel registro

Nella pagina principale la card "Compagnia" mostra le barre dei PF con i pulsanti −/+ e il contatore dei turni nel dungeon con la luce.

I dati si salvano da soli nel browser. Con "Esporta campagna" ottieni un file JSON da tenere come backup o da portare su un altro computer.
