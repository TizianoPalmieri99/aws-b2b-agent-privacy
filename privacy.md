Tiziano Palmieri / AWS B2B Agent e AWS B2B Agent - Dati

# Informativa privacy

Ultimo aggiornamento: 16 novembre 2026

**Progetti in fase di sviluppo.** Questa informativa riguarda
AWS B2B Agent e l'app dedicata AWS B2B Agent - Dati. Sono progetti riservati
al titolare, non servizi aperti ad altri utenti. La configurazione di
portabilità è disponibile ma richiede il consenso personale e l'inserimento
del token nel programma Windows; il precedente test OAuth locale è fermo.

## 1. Chi gestisce l'app

Tiziano Palmieri, Italia, gestisce AWS B2B Agent e AWS B2B Agent - Dati, destinati
al supporto della propria attività professionale. Per domande sul trattamento
dei dati: [palmieritiziano99@gmail.com](mailto:palmieritiziano99@gmail.com).

## 2. Ambito e stato del servizio

L'app è riservata all'uso del solo titolare. Non è un servizio
di accesso aperto ad altri utenti. La sola lettura di questa pagina non
collega un account.

Il test riguarda esclusivamente l'autenticazione tramite
LinkedIn e una lettura dei dati di base autorizzati. Pubblicazione, commenti,
messaggi, inviti e altre azioni sull'account restano disabilitati.

## 3. Dati e permessi del test

Solo dopo l'accesso e il consenso personale sul sito ufficiale LinkedIn,
il test riceve un token e interroga l'endpoint ufficiale userinfo.
Richiede soltanto i permessi `openid` e `profile`.
Questi consentono di ricevere un identificativo
dell'account, il nome, il riferimento alla foto del profilo e le informazioni
tecniche presenti nella risposta di autenticazione, come scadenza e lingua,
se disponibili. Non è previsto il permesso `email`.

Il flusso OAuth utilizza un codice di autorizzazione temporaneo e token tecnici.
L'app non deve richiedere la password di LinkedIn né cookie di sessione.
L'indirizzo email indicato in questa pagina è un recapito di contatto fornito
dal titolare, non un dato recuperato tramite l'API.

## 4. Finalità e contatti

Il test verifica il funzionamento del collegamento con l'account del titolare,
su sua richiesta. Il trattamento è limitato a questo controllo tecnico,
sulla base del legittimo interesse a verificare il corretto funzionamento
e la sicurezza dell'integrazione per la propria attività. Non comporta
decisioni automatizzate con effetti giuridici o significativi.

Chi scrive volontariamente al recapito indicato fornisce l'indirizzo email,
il contenuto della richiesta ed eventuali allegati. Questi dati sono utilizzati
per rispondere e gestire la richiesta, sulla base del legittimo interesse
a dare seguito alle comunicazioni ricevute. Non inviare password o token.
I dati non sono destinati a pubblicità, vendita o profilazione commerciale.

L'autorizzazione tecnica OAuth è distinta dalla base giuridica del trattamento.
Qualsiasi funzione ulteriore richiederà una nuova valutazione e un aggiornamento
dell'informativa prima della sua attivazione.

## 5. Conservazione e sicurezza

Il precedente test OAuth viene eseguito localmente sul dispositivo del titolare. Il Client Secret
dell'app si inserisce nel modulo locale ed è trasmesso solo all'endpoint OAuth
ufficiale LinkedIn. Codice temporaneo, token e dati del profilo sono usati in
memoria per il test; non sono salvati su disco, nel database, nei report o nei log.
Non sono inviati a servizi di intelligenza artificiale. Il risultato mostra
soltanto se il test è riuscito, senza rendere visibili dati del profilo.

I riferimenti ai dati temporanei vengono eliminati dopo il test o in caso
di errore; il programma locale termina dopo 15 minuti. Non viene garantito
l'azzeramento fisico della memoria del dispositivo. Il browser riceve un cookie
tecnico locale di durata massima 15 minuti per proteggere il collegamento.
Il codice temporaneo può transitare nella navigazione del browser: non
condividerne l'indirizzo o la cronologia.

Le comunicazioni inviate al recapito di contatto sono conservate per il tempo
necessario a gestire la richiesta e gli eventuali obblighi di legge o esigenze
di tutela dei diritti. Le eventuali informazioni conservate da LinkedIn e
dal fornitore di hosting seguono i termini delle rispettive informative.

## 6. Servizi esterni e hosting della pagina

Durante il test, LinkedIn riceve le richieste di autenticazione
e le chiamate autorizzate e tratterà i dati secondo la propria
[informativa privacy](https://www.linkedin.com/legal/privacy-policy).

Questa informativa è pubblicata su GitHub. L'eventuale versione web
dedicata è ospitata su GitHub Pages.
GitHub tratta dati tecnici delle visite, incluso l'indirizzo IP, per finalità
descritte nella propria
[informativa privacy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
Il file della pagina non contiene moduli, script, strumenti di analisi,
font esterni o immagini remote.

GitHub ospita il testo pubblico, non i token del collegamento.
L'infrastruttura di GitHub può comportare trattamenti fuori dallo Spazio
economico europeo; le garanzie applicate sono descritte nella sua informativa,
nella sezione sui trasferimenti internazionali. L'eventuale uso di altri servizi,
inclusi servizi di intelligenza artificiale, sarà descritto prima di introdurlo
nel trattamento dei dati recuperati tramite API.

## 7. Revoca e richieste sui dati

L'accesso concesso può essere revocato dalle impostazioni
LinkedIn relative alle applicazioni o ai servizi autorizzati.
La revoca impedirà il successivo accesso autorizzato; non cancellerà
automaticamente eventuali copie già conservate. Il test non conserva copie
del profilo. Scartare un token localmente non revoca l'autorizzazione
concessa su LinkedIn; l'autorizzazione può restare attiva fino alla revoca.

Per richieste di accesso, rettifica, cancellazione, limitazione,
opposizione o portabilità, nei casi previsti dalla normativa applicabile,
scrivere a [palmieritiziano99@gmail.com](mailto:palmieritiziano99@gmail.com).
Resta possibile presentare un reclamo al
[Garante per la protezione dei dati personali](https://www.garanteprivacy.it/).

## 8. App dedicata alla portabilità: AWS B2B Agent - Dati

È disponibile un'integrazione distinta per il prodotto ufficiale Member Data
Portability API (Member), dedicato all'accesso ai propri dati LinkedIn
da parte dei membri idonei nello Spazio economico europeo e in Svizzera.
Non si tratta di accesso al feed generale o di ricerca di altri profili.

Lo scope richiesto è `r_dma_portability_self_serve`. A seconda
dei domini effettivamente disponibili, il prodotto permette di recuperare
dati del proprio account, profilo, post, messaggi, inviti e attività social.
I messaggi e le interazioni possono contenere anche dati di interlocutori.
La finalità prevista è analizzare i dati professionali del titolare e
preparare bozze di contenuti o risposte. Non abilita invii o pubblicazioni.

La versione attuale verifica l'autorizzazione tramite l'endpoint ufficiale
memberAuthorizations e permette, solo su richiesta, la lettura di una pagina
del dominio PROFILE. Sono conservati in memoria per l'analisi soltanto nome,
cognome, titolo professionale, riepilogo, settore e siti web, se presenti.
Indirizzo, data di nascita e altri campi non professionali sono esclusi
dal risultato. Non sono attivate letture di messaggi, post o contatti.

Il token viene inserito in una finestra nativa sul dispositivo del titolare
e conservato nel Gestore credenziali del suo account Windows, separato da
Git, chat e file del progetto. Resta conservato fino alla rimozione tramite
il programma o il Gestore credenziali; la scadenza o la revoca LinkedIn ne
possono impedire prima l'utilizzo. La cancellazione locale non equivale
alla revoca su LinkedIn e viceversa.

La finalità è consentire al titolare di analizzare il proprio profilo
professionale con l'assistente, sulla base del legittimo interesse a gestire
la propria attività. Il programma non salva le risposte grezze su disco.
Quando viene richiesta l'analisi con l'assistente, i campi professionali
selezionati sono resi disponibili al servizio OpenAI utilizzato dal titolare.
La conversazione e i suoi dati seguono le impostazioni del suo account e
l'[informativa OpenAI](https://openai.com/policies/privacy-policy/),
incluse conservazione e trasferimenti internazionali. Non si garantisce
l'eliminazione della cronologia tramite la sola revoca del token.

Per l'hosting pubblico, il collegamento LinkedIn e l'assistente si applicano
le informative dei rispettivi fornitori anche per i trattamenti fuori dallo
Spazio economico europeo e le relative garanzie. Ulteriori domini di dati
o modalità di conservazione richiederanno un aggiornamento prima dell'uso.

Secondo la documentazione LinkedIn, il consenso alla portabilità può
avviare l'archiviazione dei dati da parte di LinkedIn per le API Snapshot
e Changelog, anche prima del loro recupero da parte dell'app.
Si applicano l'[informativa LinkedIn](https://www.linkedin.com/legal/privacy-policy)
e le condizioni specifiche presentate dal prodotto.

## 9. Aggiornamenti

Il testo sarà aggiornato prima di aggiungere
finalità, permessi, destinatari o modalità di conservazione diverse da quelle
descritte. La data della versione è indicata all'inizio della pagina.

AWS B2B Agent e AWS B2B Agent - Dati sono progetti di Tiziano Palmieri.
Non è un prodotto ufficiale di LinkedIn o Amazon Web Services.
