# ⚙️ Esercitazione A — Simulatore di automazione

**Simulatore di automazione** è una mini web app didattica che mostra come funziona una sequenza automatizzata: un **evento** fa partire il processo, una **condizione** già programmata viene valutata, viene eseguita un’**azione** prevista e il flusso arriva all’**arresto**.

L’esercitazione è pensata per il **Modulo B** del percorso sull’IA nella Pubblica Amministrazione e aiuta i partecipanti non tecnici a capire la differenza tra un’automazione basata su regole e un sistema di IA generativa.

## 🎯 A chi è rivolto

L’esercitazione è pensata per:

- funzionari ed esecutori della Pubblica Amministrazione;
- personale non tecnico che inizia a esplorare automazioni e IA;
- responsabili di uffici che devono valutare processi ripetitivi;
- formatori e docenti che vogliono spiegare in modo semplice evento, condizione, azione e arresto;
- partecipanti ai percorsi di upskilling sull’IA nella PA.

## 🧠 Obiettivo formativo

L’app mostra che un’automazione:

1. parte quando si verifica un **evento**;
2. valuta una **condizione** già programmata;
3. svolge un’**azione** già prevista;
4. raggiunge l’**arresto**, senza decidere autonomamente nuovi compiti.

Il messaggio centrale è semplice:

> Un’automazione esegue istruzioni già definite. Può seguire percorsi diversi in base ai dati, ma non inventa da sola nuove regole.

## 🕹️ Come funziona

La durata indicativa è di **3–5 minuti**.

1. Apri `index.html` nel browser.
2. Scegli uno dei due scenari disponibili.
3. Modifica soltanto il dato di ingresso.
4. Premi **Avvia simulazione**.
5. Osserva i quattro passaggi: evento, condizione, azione e arresto.
6. Cambia il dato e ripeti la simulazione.
7. Confronta i risultati: è cambiata la regola oppure soltanto il dato?

### Risposta attesa

Cambia soltanto il **dato in ingresso**. La regola predefinita seleziona un ramo diverso, ma non inventa nuovi passaggi né assume decisioni autonome.

## 🧩 I due scenari

| Scenario | Evento | Condizione | Azione possibile |
|---|---|---|---|
| **Segnalazione ricevuta** | Arriva un modulo di segnalazione simulato | I campi necessari sono completi? | Notifica per l’operatore oppure richiesta di integrazione |
| **Scadenze dell’ufficio** | È giovedì alle 9:00, orario simulato | Ci sono attività in scadenza nei prossimi 7 giorni? | Preparazione di un elenco oppure nessun avviso |

In entrambi i casi, le azioni sono **solo rappresentate a schermo**: nessuna email viene inviata e nessun dato reale viene modificato.

## 💻 Come usare l’app

L’app è una **web app statica autonoma**, contenuta in un unico file `index.html`.

- Non richiede account, registrazione o installazione.
- Non utilizza modelli AI, agenti o skill.
- Non invia email, notifiche o richieste di rete.
- Non modifica gestionali o sistemi dell’ente.
- Non salva dati personali.
- Funziona anche offline.

### Avvio locale

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Scegli lo scenario e avvia la simulazione.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/AI-Simulatore-di-automazione.git](https://github.com/gigicogo/AI-Simulatore-di-automazione.git)
cd AI-Simulatore-di-automazione
```

## 🧪 Prova per l’aula

La prova guidata dura circa **3 minuti**:

1. Avvia la simulazione con il primo dato.
2. Cambia il dato, ad esempio da “Sì, è completa” a “No, è incompleta”.
3. Ripeti la simulazione.
4. Confronta i due percorsi.
5. Chiedi al gruppo: **“È cambiata la regola, oppure soltanto il dato in ingresso?”**

Questa attività è utile per introdurre la differenza tra:

- un’automazione basata su regole fisse;
- un assistente AI generativo;
- un agente che potrebbe pianificare o eseguire più azioni.

## 🔐 Sicurezza e limiti

- Tutta l’elaborazione avviene nel browser.
- Tutti i dati mostrati sono inventati.
- Le azioni sono simulate e non producono effetti reali.
- Nessuna informazione della PA deve essere inserita nell’esercizio.
- Il modello è volutamente semplice: le automazioni reali possono includere più condizioni, eccezioni, passaggi e controlli.

## 🛠️ Personalizzazione

Per aggiornare i contenuti:

1. Apri `index.html` in un editor di testo.
2. Individua l’oggetto JavaScript `scenarios`, alla fine del file.
3. Modifica testi, domande, regole, messaggi e risultati.
4. Per cambiare i colori principali, intervenire sulle variabili CSS nel blocco `:root`.

Non è necessaria alcuna build, dipendenza, chiave API o configurazione aggiuntiva.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi scenari per la PA.
- Visualizzazione di regole più complesse, con più condizioni o eccezioni.
- Confronto esplicito tra automazione a regole e assistente AI.
- Versione inglese dell’interfaccia.
- Materiali per il docente e schede di lavoro per i partecipanti.
- Integrazione con esempi di workflow reali, resi anonimi.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi scenari, miglioramenti didattici, correzioni e materiali di supporto.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo scenario.
3. Mantieni la struttura a quattro passaggi: evento, condizione, azione e arresto.

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
