# CassazioneHybridRAG
Un progetto di studio in corso per la raccolta, l'estrazione e l'analisi di dati testuali non strutturati provenienti dalle sentenze civili della Corte di Cassazione per creare un sistema di information retrieval. Essendo un progetto di studio di un principiante in questo ambito, consigli, suggerimenti e contributi a questo progetto sono più che benvenuti!

## Obiettivo del progetto
Sperimentare e prototipare una pipeline end-to-end per il trattamento di documenti giuridici, partendo dall'automazione del recupero dati fino alla preparazione dei testi per future applicazioni di Information Retrieval e RAG (Retrieval-Augmented Generation).

## Stato dei lavori

* **Web Scraping Automation:** Script in Python basato su Selenium per l'interrogazione automatizzata dell'archivio delle sentenze civili e l'estrazione dei documenti di interesse.
* **Data Cleaning & Parsing:** Moduli per la pulizia del testo, la gestione dei margini e la normalizzazione strutturata dei PDF estratti.
* **Chunking:** Divisione del testo in chunks.
* **Estrazione Riferimenti Normativi** Estrazione riferimenti normativi per creare nodi del futuro grafo.
* **Creazione Vector Database** generazione embedding dei chunk delle referenze con - **Embedding Model:** [dlicari/Italian-Legal-BERT](https://huggingface.co/dlicari/Italian-Legal-BERT) e popolamento del database vettoriale tramite Chroma
*  **Creazione grafo (in corso)**

* **Linguaggio:** Python

