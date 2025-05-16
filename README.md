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

### 🧪 Esempio guidato: Analisi NLP di una frase

Per comprendere meglio le operazioni NLP affrontate negli esercizi, utilizziamo una semplice frase in italiano:

> **"Il gatto salta sul tavolo e beve il latte."**

Vediamo passo per passo cosa accade durante ogni fase dell’elaborazione linguistica automatica:

---

📌 **1. Tokenization**  
Il testo viene suddiviso in unità minime, chiamate *token*:  
`[Il, gatto, salta, sul, tavolo, e, beve, il, latte, .]`

---

📌 **2. POS Tagging**  
A ogni token viene assegnata una **categoria grammaticale**:  
- `gatto` → NOUN (nome)  
- `salta` → VERB (verbo)  
- `sul` → ADP (preposizione articolata)  
- `latte` → NOUN

---

📌 **3. Named Entity Recognition (NER)**  
In questa frase non sono presenti entità nominate (come persone o luoghi), quindi **nessuna entità viene riconosciuta**.  
In frasi più complesse, spaCy può identificare:  
`Luca Bianchi` → `PER` (persona), `Roma` → `LOC` (luogo), ecc.

---

📌 **4. Lemmatization**  
Ogni parola viene trasformata nella sua forma base (*lemma*):  
- `salta` → `saltare`  
- `beve` → `bere`  
- `gatto` → `gatto`

---

📌 **5. Dependency Parsing**  
Analizziamo **la struttura grammaticale**:  
- `gatto` è il soggetto (`nsubj`) del verbo `salta`  
- `latte` è l’oggetto (`obj`) del verbo `beve`  
- `tavolo` è il complemento di luogo (`obl`)

---

📌 **6. Vocabulary Construction**  
Costruiamo un dizionario dei lemmi presenti nel testo (escludendo punteggiatura e parole irrilevanti):  
`{"gatto": 1, "saltare": 1, "tavolo": 1, "bere": 1, "latte": 1}`

---

📌 **7. Stop Word Filtering**  
Filtriamo parole poco informative come articoli e congiunzioni:  
**Rimangono:** `gatto`, `salta`, `tavolo`, `beve`, `latte`

---

📌 **8. Visualizzazioni con displacy**  
Attraverso grafici interattivi visualizziamo:  
- **Le relazioni sintattiche**, con archi che collegano soggetto-verbo-oggetto
- **Le entità nominate** (se presenti), evidenziate nel testo

---

Tutti gli esercizi sono implementati in Python e pensati per essere eseguiti in **Google Colab** o **Jupyter Notebook**, con esempi chiari e commentati.

📂 Percorso: `notebooks/nlp/`


---

## 📌 Note

Il progetto è in continuo aggiornamento, e ogni esercizio è pensato per essere auto-contenuto e ben documentato.

> Per domande, idee o contributi, sentiti libero di aprire una issue o inviare una pull request!
