# Roby Club — Gestionale Allievi

Web app per uso interno della scuola di danza Roby Club.

## Funzioni

- Ricerca e schede anagrafiche degli allievi
- Gestione dei corsi e assegnazione alle schede
- Mensilità da settembre ad agosto, distinte per anno accademico
- Note individuali e impostazioni generali

## Architettura

L'interfaccia è contenuta in `index.html`. Utilizza Firebase Authentication e Cloud Firestore per l'accesso e il salvataggio. Nessuna password deve essere pubblicata su GitHub.

## Pubblicazione

In **Settings → Pages** selezionare **Deploy from a branch**, branch `main`, cartella `/(root)`, e salvare.

Indirizzo previsto: https://beyorizon.github.io/robyclub-gestionale/

Prima dell'uso con dati reali configurare le regole Firestore per consentire l'accesso al solo amministratore. Il codice del sito è pubblico, il database no.
