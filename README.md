# MyPizzeria

Dosi, tempi e piano passo passo per la pizza fatta in casa. Il lievito è calcolato con la formula del Calcolapizza della Confraternita della Pizza.

## Pubblicare su GitHub Pages

1. Crea un repository (per esempio `mypizzeria`) e carica **tutti** i file di questa cartella, compresa `icons/`.
2. Nel repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
3. Dopo un minuto l'app è su `https://<tuo-utente>.github.io/mypizzeria/`.

## Installare sul telefono

- **Android (Chrome):** apri l'indirizzo, menu ⋮ → **Installa app** (o «Aggiungi a schermata Home»).
- **iPhone (Safari):** apri l'indirizzo, tasto Condividi → **Aggiungi alla schermata Home**.

Una volta aperta, funziona anche senza rete.

## Portare i dati dall'app in Claude

I dati restano sul dispositivo e ogni indirizzo ha i suoi. Per spostarli:
1. Nell'app in Claude: ⚙ Impostazioni → **Salva un backup**.
2. Nell'app installata: ⚙ Impostazioni → **Carica un backup**.

## Aggiornare

Sostituisci `index.html` e cambia `VERSION` in `sw.js` (per esempio `mypizzeria-2.0.1`). Alla riapertura l'app avvisa della nuova versione.

## Cosa cambia rispetto all'app in Claude

- **Chiedi al pizzaiolo** non c'è: usa Claude, che qui non è collegato.
- **Importa una ricetta** legge solo le dosi principali (farina, acqua, sale, olio, lievito); i passi li aggiungi tu.
