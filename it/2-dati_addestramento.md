# GiuliaAI VTuber Project Documentation

*[Indice](https://github.com/GiuliaAI/legal/blob/main/README.md)*

## 2. Dati di Addestramento

### Origine dei Dati
L'addestramento di GiuliaAI si basa su una combinazione di diversi set di dati:
- **Common Crawl**: Un vasto archivio di dati raccolti dal web.
- **Wikipedia**: Contenuti enciclopedici aggiornati e diversificati.
- **BooksCorpus**: Una collezione di libri di vario genere.
- **OpenSubtitles**: Dialoghi e sottotitoli di film e serie TV.
- **Chat del Canale Twitch**: Messaggi e interazioni raccolte dal canale Twitch di GiuliaAI.
- **Contenuti di YouTube**: Video e commenti pubblici.
- **Dati Pubblicamente Disponibili**: Informazioni su manga, anime, meme virali, video virali e notizie virali.

### Qualità dei Dati
Per garantire la qualità dei dati, vengono implementate le seguenti misure tecniche:
- **Pulizia dei Dati**: Usiamo tecniche di preprocessing, come la rimozione di stop words, la correzione automatica degli errori ortografici e la deduplicazione, per migliorare la qualità del dataset.
- **Normalizzazione**: Applichiamo processi di normalizzazione, come la conversione di tutti i testi in minuscolo e l'unificazione dei formati delle date, per assicurare coerenza nei dati.
- **Bilanciamento**: Utilizziamo tecniche di oversampling e undersampling per bilanciare il dataset, riducendo i bias e migliorando l'equità del modello.
- **Validazione e Test**: Dividiamo il dataset in set di addestramento, validazione e test, usando k-fold cross-validation per valutare le prestazioni del modello in modo robusto e prevenire overfitting.
- **Aggiornamento Continuo**: Aggiorniamo periodicamente i dataset con nuove informazioni rilevanti, mantenendo il modello aggiornato con le tendenze attuali e migliorando continuamente le sue prestazioni.

### Privacy e Conformità GDPR
Il trattamento dei dati di GiuliaAI è conforme al GDPR. Ecco come vengono gestiti i dati personali:
- **Anonimizzazione**: I dati personali vengono anonimizzati attraverso tecniche come la pseudonimizzazione e l'aggregazione, per proteggere la privacy degli utenti.
- **Consenso**: I dati vengono raccolti solo da fonti pubbliche o con il consenso esplicito degli utenti, assicurando che tutte le raccolte di dati siano legittime e trasparenti.
- **Trasparenza**: Gli utenti sono informati su come i loro dati vengono utilizzati. Viene offerta loro la possibilità di accedere, rettificare e cancellare i loro dati in qualsiasi momento.
- **Misure di Sicurezza**: Implementiamo protocolli di sicurezza come la crittografia dei dati in transito e a riposo, e controlli di accesso basati su ruoli per proteggere i dati da accessi non autorizzati.
