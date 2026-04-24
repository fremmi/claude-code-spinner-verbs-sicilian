# Contribuire

Grazie per voler aggiungere il tuo tocco siciliano a questo repo! 🌋

## Come contribuire

1. **Fai un fork** del repo
2. **Crea un branch** con nome descrittivo: `aggiungi-verbi-palermitani`, `fix-glossario-scattiannu`, etc.
3. **Aggiungi i tuoi verbi** nel file appropriato
4. **Testa** che il JSON sia valido: `jq . spinner-verbs.json`
5. **Apri una Pull Request** descrivendo cosa hai aggiunto e da quale zona della Sicilia viene il termine

## Regole di stile

### Formato dei verbi

- **Usa il gerundio siciliano**: desinenza `-annu` (prima coniugazione) o `-ennu` (seconda/terza). Esempi: `Travagghiannu`, `Sciddricannu`, `Scummigghiennu`.
- **Lunghezza**: tienili sotto le ~25 caratteri quando possibile. Lo spinner del terminale ha spazio limitato.
- **Capitalizza la prima lettera**, tutto il resto minuscolo (stile "Sentence case"). No `ADDUMANNANNU`, no `addumannannu`.
- **Frasi idiomatiche** (tipo `Mizzica chi travagghiu`) vanno bene ma tienile in coda agli array, dopo i verbi puri.

### Ortografia

La scrittura del siciliano non è standardizzata come quella dell'italiano. Linee guida pragmatiche per questo repo:

- `gh` per il suono /j/ in parole come `pigghiari`, `travagghiari`
- `dd` per la cacuminale: `beddu`, `iddu`, `chiddu`
- Trema sulla `ï` dove la pronuncia lo richiede: `talïannu`
- Apostrofo per elisioni davanti a vocale: `l'Etna`, `d'amuri`

Se il tuo dialetto locale scrive diversamente, segnalalo nella PR e lo discutiamo — ci stanno anche più varianti della stessa parola purché sia chiaro di cosa si tratta.

### Glossario

Se aggiungi un verbo **non immediatamente comprensibile**, aggiorna anche la tabella glossario nel [README](./README.md) con:

- Il verbo
- La traduzione italiana
- Un esempio di quando avrebbe senso vederlo scorrere nello spinner
- (Opzionale) la zona della Sicilia, se è un termine molto locale

### Contenuti

- **Niente parolacce gratuite**. Un `minchia` occasionale è folklore, una bestemmia no.
- **Niente contenuti offensivi** contro persone, gruppi, territori.
- **Sì all'autoironia siciliana** — è metà del divertimento.

## Proporre un nuovo preset

Se pensi che serva un nuovo file JSON tematico (es. `spinner-verbs-palermo.json`, `spinner-verbs-agrumi.json`, `spinner-verbs-pasticceria.json`), apri prima una issue per discutere l'idea.

## Dubbi?

Apri una issue con il tag `question`. Si ragiona insieme.

*Fozza ca' stuppamu!* 🍋
