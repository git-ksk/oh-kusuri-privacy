# Informativa sulla privacy

**Ultimo aggiornamento: 18 settembre 2026**

Questa informativa descrive come lo sviluppatore tratta le informazioni in Oh!Le mie medicine (l’“App”).

## 1. Dati su farmaci e assunzioni

L’App non richiede registrazione o account. Farmaci, integratori, programmi, cronologia delle assunzioni, scorte e note restano normalmente sul dispositivo. L’App non sincronizza continuamente questi dati con il nostro cloud. Nomi dei farmaci, note libere, note sui sintomi e termini di ricerca grezzi non vengono inviati come campi personalizzati di Firebase Analytics o Crashlytics.

## 2. Cambio dispositivo

Solo quando avvii esplicitamente il cambio dispositivo dalle impostazioni, l’App cifra sul dispositivo i dati relativi a farmaci e assunzioni e invia i dati cifrati a un servizio di trasferimento temporaneo.

- I dati sono cifrati con una chiave derivata localmente dal codice di recupero. Il normale trattamento server non riceve in chiaro nomi dei farmaci, cronologia, note o sintomi.
- I dati cifrati restano disponibili per un massimo di **72 ore**. Dopo un ripristino riuscito o una revoca vengono resi inutilizzabili ed eliminati appena possibile. La scadenza di 72 ore resta la protezione finale in caso di problemi temporanei.
- Non conserviamo il codice di recupero e non possiamo recuperare o riemettere un codice perso.
- Usiamo Firebase App Check e limiti di richieste contro gli abusi. Le informazioni di rete possono essere elaborate a tale scopo; nei metadati operativi salviamo un identificatore derivato irreversibilmente anziché l’indirizzo IP grezzo.
- Il trasferimento è temporaneo e esplicito, non un backup con account né una sincronizzazione continua.

## 3. Ricerca e suggerimenti

Nei paesi supportati, il termine cercato può essere inviato a servizi pubblici o terzi oppure a un proxy gestito da noi per restituire suggerimenti. Non aggiungiamo cronologia, scorte, note o sintomi a tali richieste.

## 4. Analisi dell’utilizzo

Usiamo **Google Firebase Analytics** per migliorare qualità e funzionalità. I dati possono includere versione dell’app, lingua, interazioni, conteggi raggruppati e informazioni tecniche. Gli eventi personalizzati non devono includere dati medici inseriti dall’utente, codici di recupero, capacità di trasferimento o payload di trasferimento. Analytics non viene usato per pubblicità o tracciamento.

## 5. Diagnostica di arresti anomali ed errori

Usiamo **Google Firebase Crashlytics**. I dati diagnostici aggiunti dall’App sono limitati a nomi di operazioni, fasi, classificazioni e codici numerici predefiniti e non includono contenuti medici o segreti di trasferimento. Non impostiamo un ID utente Crashlytics personalizzato. La raccolta può essere disattivata nelle impostazioni; la modifica può diventare pienamente effettiva al riavvio successivo.

## 6. Pubblicità e tracciamento

L’App non mostra annunci, non usa Google AdMob e non effettua tracciamento pubblicitario tramite ATT.

## 7. Servizi di terze parti e cloud

L’App utilizza Firebase e Google Cloud. I dati cifrati di trasferimento e i metadati operativi minimi vengono temporaneamente elaborati e conservati su infrastruttura Google Cloud gestita da noi.

- [Norme sulla privacy di Google](https://policies.google.com/privacy)
- [Privacy e sicurezza Firebase](https://firebase.google.com/support/privacy)
- [Informativa sulla privacy di Google Cloud](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Modifiche

Potremmo aggiornare questa informativa quando cambiano le funzionalità o i servizi utilizzati.

## 9. Contatti

- **Email**: k.lifetime.app+ohkusuri-support@gmail.com

---
*La versione giapponese è la versione di riferimento.*
