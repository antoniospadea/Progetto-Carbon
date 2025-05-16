# 🌱 Progetto-Carbon

**Esercizi di Machine Learning e Deep Learning** realizzati nell’ambito del corso di **Rigenerazione**.

Questo repository raccoglie una serie di esempi, notebook e modelli sviluppati per comprendere e applicare tecniche di apprendimento automatico e profondo, con un focus su:

- 📊 Preprocessing e analisi dei dati
- 🧠 Modelli di classificazione e regressione
- 🔍 Tecniche di ottimizzazione e validazione
- 🤖 Reti neurali semplici (MLP), CNN e RNN
- 🧪 Applicazioni a problemi reali o simulati legati alla rigenerazione urbana e ambientale

---

## 📁 Struttura del progetto

- `notebooks/` – Notebook interattivi divisi per tema ed esercizio
- `data/` – Dati utilizzati (in formato CSV, immagini o JSON)
- `models/` – Architetture salvate e pesi pre-addestrati (opzionale)
- `utils/` – Funzioni comuni di supporto (metriche, visualizzazione, ecc.)

---

## 🚀 Obiettivi formativi

Il progetto ha lo scopo di:
- Allenare le competenze pratiche di ML/DL
- Favorire l’apprendimento sperimentale attraverso esempi concreti
- Collegare l’AI a contesti di rigenerazione sostenibile

---

## 🧠 Requisiti principali

- Python 3.9+
- `numpy`, `pandas`, `matplotlib`
- `scikit-learn`, `tensorflow` o `pytorch`
- (opzionale) `jupyterlab` o Google Colab

---

## 🧠 Esercizi di NLP (Natural Language Processing)

Questa sezione contiene esercizi introduttivi sul trattamento automatico del linguaggio naturale con **spaCy**, applicati alla lingua italiana.

Ogni esercizio è focalizzato su un singolo concetto fondamentale del NLP, utile per costruire pipeline linguistiche, motori di ricerca semantici, e classificatori testuali.

### 📘 Esercizi contenuti:

#### 📌 1. TOKENIZATION — Suddividere il testo in unità minime
Suddivide un testo in parole, segni di punteggiatura e simboli, detti *token*.

#### 📌 2. POS TAGGING — Etichettatura grammaticale
Assegna a ogni parola la sua **categoria grammaticale** (nome, verbo, aggettivo, ecc.).

#### 📌 3. NER — Named Entity Recognition
Riconosce le **entità nominate** nel testo, come persone, città, date, organizzazioni.

#### 📌 4. LEMMATIZATION — Forma base della parola
Riconduce ogni parola alla sua **forma base (lemma)**: ad es. "correvano" → "correre".

#### 📌 5. DEPENDENCY PARSING — Struttura sintattica
Analizza **le relazioni grammaticali** tra parole, come soggetto-verbo-oggetto.

#### 📌 6. VOCABULARY — Costruzione del dizionario dei lemmi
Estrae tutti i lemmi univoci presenti in un testo, e ne calcola la frequenza.

#### 📌 7. STOP WORD FILTERING — Rimozione parole vuote
Filtra parole comuni che non aggiungono significato semantico (es. "il", "di", "e").

#### 📌 8. VISUALIZZAZIONI — Con displacy
Visualizza:
- le **relazioni sintattiche** tra parole (`style="dep"`)
- le **entità nominate** evidenziate nel testo (`style="ent"`)

---

Tutti gli esercizi sono implementati in Python e pensati per essere eseguiti in **Google Colab** o **Jupyter Notebook**, con esempi chiari e commentati.

📂 Percorso: `notebooks/nlp/`


---

## 📌 Note

Il progetto è in continuo aggiornamento, e ogni esercizio è pensato per essere auto-contenuto e ben documentato.

> Per domande, idee o contributi, sentiti libero di aprire una issue o inviare una pull request!
