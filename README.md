# Progetto di Sentiment Analysis su Reddit

## Introduzione
Questo repository ospita un progetto di analisi del sentimento su Reddit, focalizzato sul caso di Giulia Cecchettin.  L'obiettivo principale è la comprensione dei sentimenti e delle emozioni espressi dagli utenti nei commenti. Attraverso un'analisi approfondita del linguaggio naturale, miriamo a estrarre insights significativi riguardo alla percezione e all'opinione della community online riguardo a questa vicenda.

## Metodologia
Il progetto è strutturato in 4 fasi:

1. **Raccolta dei Dati**: Utilizzando le API di Reddit, sono stati estratti commenti pertinenti al caso di Giulia Cecchettin. Questa fase è cruciale per ottenere un campione rappresentativo delle opinioni degli utenti sulla piattaforma.

2. **Pulizia dei Dati**: I dati raccolti sono stati sottoposti a una fase di pulizia, che include l'eliminazione delle stop-words. Questo passaggio è essenziale per ridurre il rumore nei dati e concentrarsi solo sulle parole chiave significative.

3. **Classificazione con Feel-it**: Per analizzare i sentimenti, è stato utilizzato il classificatore fornito dalla libreria Feel-it. Questa libreria offre un approccio efficace per classificare il testo in base alle emozioni espresse, consentendo una valutazione più approfondita dei dati.

4. **Analisi dei Dati e Creazione di Grafici**: I risultati ottenuti dal classificatore Feel-it sono stati sottoposti a un'analisi dettagliata. I dati sono stati rappresentati attraverso grafici per visualizzare in modo chiaro la distribuzione dei sentimenti e delle emozioni nel tempo all'interno della community di Reddit.

## Tecnologie Utilizzate
Il progetto è stato sviluppato utilizzando le seguenti tecnologie:

- Linguaggio di programmazione: Python
- Librerie principali: PRAW (Python Reddit API Wrapper), Feel-it
- Ambiente di sviluppo: Jupyter Notebook

## Installazione
Per eseguire correttamente il progetto sul proprio sistema, seguire i seguenti passaggi:

1) Assicurarsi di avere installato Python versione 3.x sul proprio sistema.
2) Clonare il repository utilizzando il comando: `git clone https://github.com/DarioDeMaio/SentimentAnalysis` 
3) Installare le librerie necessarie eseguendo il seguente comando nella console: `pip install -r requirements.txt` 

## License

Questo progetto è concesso in licenza con la licenza MIT. Per ulteriori informazioni, fare riferimento al file `LICENSE`.
