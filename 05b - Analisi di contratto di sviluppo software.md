# Analisi di contratto di sviluppo software

Corso: Diritto dell'Informatica T — A.A. 2025/2026 — Prof.ssa Claudia Cevenini

> Questo file analizza le **clausole essenziali** di un contratto d'opera per la consulenza avente ad oggetto lo sviluppo di un sistema software. Per ciascuna clausola si indica cosa deve contenere e i riferimenti normativi rilevanti.

---

## Tipologia contrattuale di riferimento

Il contratto di sviluppo software è inquadrabile come **contratto d'opera intellettuale**:

| Norma | Contenuto |
|---|---|
| **Art. 2222 c.c.** — Contratto d'opera | "Quando una persona si obbliga a compiere verso un corrispettivo un'opera o un servizio, con lavoro prevalentemente proprio e **senza vincolo di subordinazione** nei confronti del committente" |
| **Art. 2230 c.c.** — Contratto d'opera intellettuale | "Il contratto che ha per oggetto una **prestazione d'opera intellettuale**" |
| **Art. 2229 c.c.** — Professioni intellettuali | Disciplina l'esercizio delle professioni intellettuali; l'ingegnere deve essere iscritto all'albo |

---

## Parte generale

### 1. Parti del contratto

Specificare i **soggetti** che concludono l'accordo:

- **Persone fisiche**: nome, cognome, data di nascita, residenza, C.F. e P.IVA
- **Persone giuridiche, enti e associazioni**: sede legale, C.F., P.IVA e **legale rappresentante**

### 2. Oggetto del contratto

Ai sensi dell'**art. 1346 c.c.**, l'oggetto del contratto deve essere *possibile, lecito, determinato o determinabile*.

Descrivere chiaramente:
- **Quale software** dovrà essere sviluppato (obiettivi, caratteristiche; eventualmente in un allegato tecnico)
- **Come** sarà rilasciato il software (es. installato presso il cliente, via web in modalità SaaS)
- **A quale titolo** si prevede la realizzazione (es. cessione dei diritti di utilizzazione economica)
- Se si adatta un software già esistente: specificare **a quale titolo** l'ingegnere ha diritto di modificarlo

### 3. Natura del contratto — contratto d'opera intellettuale

Rilevante ai fini della responsabilità e dell'autonomia professionale:

- L'ingegnere informatico non è un lavoratore subordinato: ha piena **autonomia organizzativa** nell'esecuzione del lavoro
- Deve essere iscritta all'albo la figura professionale quando richiesto dalla legge
- La **diligenza** richiesta è quella del **professionista qualificato** (art. 1176, c. 2 c.c.)

---

## Clausole operative essenziali

### 4. Corrispettivo e modalità di pagamento

Specificare:
- **Importo** del corrispettivo (fisso, a consumo, misto)
- **Scadenze di pagamento** (es. acconto all'avvio, saldi a milestone, saldo finale a consegna)
- **Modalità di pagamento** (bonifico, ecc.) e termini di emissione fattura
- Eventuali **penali** per ritardo nel pagamento da parte del committente

### 5. Tempistiche di realizzazione e milestone

- Indicare le **date di consegna** intermedie (milestone) e quella finale
- Stabilire le **conseguenze** del mancato rispetto delle tempistiche (penali, diritto di recesso)
- Prevedere procedure per la **proroga giustificata** dei termini

### 6. Variazioni necessarie

Clausola cruciale per gestire i cambiamenti in corso d'opera:

- **Variazioni richieste dal committente**: specificare come si formalizzano (richiesta scritta, preventivo aggiuntivo, accettazione)
- **Variazioni necessarie per eventi sopravvenuti** imprevedibili e non imputabili a nessuna delle parti: prevedere obblighi di rinegoziazione di specifiche tecniche, tempistiche e prezzo
- **Recesso per variazioni eccessive**: è utile prevedere la possibilità di recesso dell'ingegnere o del committente quando le variazioni risultino troppo onerose o rendano impossibile la prosecuzione; in caso di recesso, definire i criteri per l'**equa indennità** all'ingegnere per l'attività già prestata

### 7. Titolo di fornitura del software al committente

Specificare **a quale titolo** il committente potrà usare il software sviluppato. Le opzioni principali sono:

| Titolo | Descrizione |
|---|---|
| **Licenza d'uso** | L'ingegnere rimane titolare dei diritti; il committente ottiene solo il diritto d'uso nei limiti pattuiti (non esclusiva, esclusiva, durata, territorio) |
| **Cessione dei diritti di utilizzazione economica** | Il committente acquisisce i diritti patrimoniali sull'opera; l'ingegnere mantiene solo il diritto morale di paternità |
| **Cessione del codice sorgente** | Può essere inclusa o meno nella cessione; rilevante per manutenzione futura e portabilità |

> **Nota**: in assenza di specifica pattuizione, per il software sviluppato su commissione si applica la disciplina dell'art. 12-bis L. 633/1941 (Legge sul Diritto d'Autore), che attribuisce i diritti di utilizzazione economica al **datore di lavoro** se l'opera è creata nell'esecuzione di un rapporto di lavoro.

### 8. Garanzia e collaudo

- Definire le modalità di **collaudo** del software (chi lo esegue, criteri di accettazione, tempi)
- Stabilire il **periodo di garanzia** successivo alla consegna (correzione di bug, difetti di conformità)
- Distinguere tra:
  - **Vizi** del software (art. 2226 c.c. — il committente deve denunciare i vizi entro 8 giorni dalla scoperta e agire entro 1 anno dalla consegna)
  - **Difformità** rispetto alle specifiche pattuitePrevedere la **garanzia di evizione** (l'ingegnere garantisce che il software non violi diritti di terzi)

### 9. Riservatezza e non divulgazione (NDA)

- Obblighi di **riservatezza reciproca** sulle informazioni scambiate durante l'esecuzione del contratto
- Specificare quali informazioni sono considerate **riservate** e per quanto tempo persiste l'obbligo dopo la fine del contratto
- Rilevante in presenza di segreti commerciali del committente (dati, algoritmi, architetture)

### 10. Trattamento dei dati personali

Obblighi derivanti dal **GDPR** (Reg. UE 2016/679):
- Se l'ingegnere tratta dati personali del committente o dei suoi clienti nell'esecuzione dell'incarico, deve essere nominato **Responsabile del trattamento** (art. 28 GDPR)
- Il contratto deve contenere (o allegare) il **DPA** (Data Processing Agreement) con le istruzioni del titolare al responsabile

### 11. Responsabilità e limitazione del danno

- Definire i casi di **esclusione della responsabilità** dell'ingegnere (cause di forza maggiore, dati errati forniti dal committente, ecc.)
- Valutare l'inserimento di un **tetto massimo al risarcimento** (cap alla liability), tipicamente pari al corrispettivo pattuito
- Prevedere obblighi di **notifica tempestiva** in caso di problemi che possano causare danni

### 12. Risoluzione delle controversie

- Scegliere il **foro competente** (giudice ordinario; arbitrato; mediazione obbligatoria ex D.Lgs. 28/2010 per controversie civili)
- Indicare la **legge applicabile** (rilevante nei contratti internazionali)

---

## Schema riepilogativo delle clausole

| Sezione | Clausola chiave | Rischio se assente |
|---|---|---|
| Parti | Identificazione completa dei soggetti | Nullità o difficoltà di esecuzione forzata |
| Oggetto | Descrizione tecnica precisa del software | Controversie su cosa è dovuto |
| Corrispettivo | Importo, scadenze, penali | Mancato pagamento senza rimedi |
| Tempistiche | Milestone, conseguenze ritardo | Ritardi indefiniti senza penali |
| Variazioni | Procedura di change management | Blocco del progetto o costi non previsti |
| IP | Titolo di fornitura (licenza vs cessione) | Incertezza su chi è titolare del software |
| Garanzia | Collaudo, periodo, vizi | Nessun rimedio per software difettoso |
| Dati personali | Nomina a Responsabile ex art. 28 GDPR | Violazione GDPR, sanzioni amministrative |
| Riservatezza | NDA | Divulgazione di informazioni riservate |
| Controversie | Foro, legge applicabile | Incertezza su dove e come litigare |
