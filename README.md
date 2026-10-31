# IFTTT PA Lab — Esercitazione A (versione potenziata)

Una web app didattica **statica e autonoma** per il Modulo B dedicato all'intelligenza artificiale nella Pubblica Amministrazione. Si ispira alla logica delle *Applets* (IF THIS → THEN THAT) di IFTTT senza riprodurre la piattaforma o collegare alcun servizio reale.

## Che cosa insegna

Il partecipante non guarda soltanto una simulazione preimpostata: **progetta un collegamento tra servizi** scegliendo:

1. **IF THIS** — il servizio e l'evento che avviano l'automazione;
2. **AND IF** — una condizione, relativa ai dati disponibili;
3. **THEN THAT** — due azioni svolte da servizi destinatari;
4. **OTHERWISE** — il comportamento nei casi non previsti dalla condizione.

Può poi provare il risultato su dati inventati diversi, confrontare la configurazione con la consegna e scaricare una semplice **scheda del processo in Markdown**.

## Le tre missioni

- **1 — Scadenze dell'ufficio:** ogni giovedì verifica scadenze a sette giorni, prepara elenco e bozza di notifica interna, annota l'assenza di scadenze.
- **2 — Segnalazioni dei cittadini:** riceve un modulo, controlla i campi, registra e crea un compito interno; le richieste incomplete devono essere gestite da una persona.
- **3 — Prenotazione di una sala comunale:** verifica domanda e disponibilità della sala; prepara soltanto bozze; i casi dubbi vanno a controllo umano.

Le missioni sono **esercizi di progettazione di automazioni**, non esercizi su agenti AI. Non utilizzano modelli linguistici.

## Pubblicazione su GitHub Pages

Il file principale si chiama `index.html` e contiene HTML, CSS e JavaScript: **nessun framework, build o dipendenza**.

Per sostituire la precedente app nel repository `AI-Simulatore-di-automazione`:

1. Aprire il repository GitHub.
2. Sostituire il file `index.html` esistente con quello di questo pacchetto (il nome deve restare esattamente `index.html`).
3. Salvare con un commit.
4. Se Pages è già configurato sulla branch pubblicata, la nuova versione comparirà sullo stesso indirizzo quando la pubblicazione avrà termine.

Si può anche pubblicare in un **nuovo repository**: `Settings → Pages → Deploy from a branch → main / root` (se la configurazione disponibile per il repository lo prevede).

Per una prova locale, è sufficiente aprire `index.html` in un browser aggiornato. Non servono server o accessi.

## Dati, privacy e sicurezza

- Tutti gli scenari e i dati sono **inventati**.
- Nessuna richiesta di account, credenziali, token, permessi o documenti.
- Nessuna chiamata di rete, API o memorizzazione su server.
- Nessuna email inviata, nessun evento di calendario creato, nessuna pubblicazione.
- Il file `.md` viene generato **localmente nel browser**.
- Le selezioni non vengono salvate automaticamente dopo la chiusura della pagina.

Il simulatore è uno strumento formativo e non una soluzione autorizzata per i processi reali dell'Ente.

## IFTTT: analogia e limiti

Nella piattaforma IFTTT reale un'Applet connette servizi attraverso trigger, azioni ed eventualmente query e filtri. L'app del corso **semplifica volutamente** questi elementi in schede comprensibili anche a chi non programma; non simula credenziali, autorizzazioni, integrazioni tecniche, gestione degli errori di rete o funzionalità soggette ai diversi piani di servizio.

Documentazione ufficiale: <https://help.ifttt.com/hc/en-us/articles/115010361348-What-is-an-Applet>

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
