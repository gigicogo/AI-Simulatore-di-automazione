# Esercitazione A — Simulatore di automazione

Mini web app statica per il **Modulo B sull'AI nella Pubblica Amministrazione**.

## Obiettivo formativo

Far capire a partecipanti non tecnici che un'automazione:

1. parte quando si verifica un **evento**;
2. valuta una **condizione** già programmata;
3. svolge una **azione** già prevista;
4. raggiunge l'**arresto**, senza decidere autonomamente nuovi compiti.

L'app include due casi fittizi: una segnalazione arrivata con un modulo e il controllo settimanale delle scadenze. **Non utilizza alcun modello AI** e non invia email, non modifica gestionali e non salva dati personali.

## Come usare l'esercizio (3-5 minuti)

1. Apri `index.html` nel browser.
2. Seleziona **Segnalazione ricevuta** e lascia impostato **Sì, è completa**.
3. Premi **Avvia simulazione**, osservando i quattro passaggi.
4. Seleziona **No, è incompleta** e ripeti.
5. Chiedi: «È cambiata la regola, oppure soltanto il dato in ingresso?».
6. Facoltativo: ripeti con **Scadenze dell'ufficio**.

**Risposta attesa:** è cambiato solo il dato. La regola predefinita seleziona un ramo diverso; non inventa nuovi passaggi. 

Non è necessaria alcuna build, dipendenza, chiave API o account aggiuntivo per utilizzare l'app. Puoi pubblicare anche il solo `index.html`.

## Sicurezza e limiti

- Tutto avviene nel browser e senza richieste di rete da parte dell'applicazione.
- Tutti i dati mostrati sono **inventati**.
- Le azioni sono **solo rappresentate a schermo**; nessuna notifica viene inviata realmente.
- Nessuna informazione della PA va inserita nell'esercizio.
- Il modello mostrato è volutamente semplice: molte automazioni reali prevedono più condizioni, eccezioni, passaggi e controlli.

## Personalizzazione

Per aggiornare i testi apri `index.html` in un editor di testo e modifica l'oggetto JavaScript `scenarios` in fondo al file. I colori principali si trovano in cima allo stile CSS, nel blocco `:root`.

## 👤 Autore e contesto

**Gianluigi Cogo** Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell'IA generativa nella Pubblica Amministrazione.

L'app nasce come esercitazione nel percorso operativo *"L'IA nella Pubblica Amministrazione — Percorso operativo per l'uso consapevole, sicuro e governato dell'IA generativa"* (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattatemi usando i social qui sotto.

- 📮 Newsletter: [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 Blog: [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ YouTube: [youtube.com/@gigicogo](https://www.youtube.com/@gigicogo)
- 💼 LinkedIn: [linkedin.com/in/gigicogo](https://it.linkedin.com/in/gigicogo)
