## hi, i'm ayana _!_ ✨🌊

**Stats + CS @ UIUC · statistician · data scientist · ml engineer**

a statistician and software engineer with a probabilist's mindset and a passion for building systems that are rigorous, honest, and actually useful. i build data pipelines, ML-powered tools, and have been experimenting with RAG systems! currently finishing a **World Cup RAG pipeline** and looking for data/ML engineering roles. 

---

## what I work with

**Statistics & ML** &nbsp; statistical modelling · stochastic processes · hypothesis testing · SVD  · TF-IDF · BM25 · scikit-learn · PyTorch · RAG pipelines · LLM evaluation · semantic search · sentence-transformers
 
**Data & pipelines** &nbsp; Python · SQL · PostgreSQL · pgvector · ChromaDB · MongoDB · ETL design · schema modeling · pandas · NumPy
 
**Infra & tooling** &nbsp; Docker · GCP · FastAPI · Git · Linux
 
**Visualization** &nbsp; PowerBI · Tableau · R (tidyverse, ggplot2, Shiny) · matplotlib · seaborn

---

## projects

### ⚽ [world-cup-rag](https://github.com/ayanapatidar/world-cup-rag) &nbsp; _(in progress)_
local, zero-cost RAG pipeline that answers rich natural-language questions about 2026 World Cup matches with conext from match facts, journalist reactions, and historical documentation. aims to help a layman understand the narrative that surrounds the beautiful game--- yes, that goal was impressive, but what does it _mean_ in the context of this player, and this team, and this match. 

- multi-collection ChromaDB vector store with custom sentence-transformers embedding wrapper (384-dim, Q&A-tuned)
- modular ingest layer scraping BBC Sport, The Guardian, Wikipedia, and football-data.org API with automatic post-match polling
- LLM synthesis via Mistral on Ollama

`Python` `ChromaDB` `sentence-transformers` `Ollama` `Mistral` `RAG`

### 🎬 [ayana-films](https://github.com/ayanapatidar/ayana-films)
a statistician's approach to taste modeling--- built on 586 personal Letterboxd entries and the MovieLens 25M dataset. the recommender and sentiment analysis aim to model my affinity towards genre and films; expect to find some drama and horror heavy picks in here, along with some guilty pleasures, but we don't have to talk about those. 

- ETL pipeline ingesting diary entries into PostgreSQL via Supabase, enriched with TMDB API metadata
- weighted SVD recommender incorporating contextual signals (rewatches, Criterion watches, theater viewings) to produce a personalized taste vector; discovered statistically meaningful rating gaps by era and language through exploratory analysis
- mood-based semantic search embedding 491 personal reviews via pgvector cosine similarity — queries scored across embeddings, mood tags, and genre signals at 25M+ record scale
- schema and indexing decisions made explicitly for query performance and extensibility

`Python` `PostgreSQL` `pgvector` `scikit-learn` `sentence-transformers` `Supabase`

 ### 🏟️ [DiscordSportsBot](https://github.com/Happy-Duck/DiscordSportsBot)
real-time sports stats bot with async database interactions and containerized deployment, worked on in a team setting. 

- external data integration wrapping TheSportsDB and API-Football for real-time player and team stats via slash commands
- async SQLAlchemy + aiosqlite modeling user subscription state across player and team entities

`Python` `SQLAlchemy` `SQLite` `Docker`

---

## outside the terminal
 
**films:** obsessive Letterboxd user. i apparently have a statistically significant bias toward 1970s european cinema, and also al pacino. i mean, can you blame me? have you seen al pacino's eyes?. [find me on Letterboxd](https://letterboxd.com/taohun)

**football:** the reason the discord bot exists. passionate about football (the real kind). fc barcelona is my special princess and i will love her forever. 

**music:** i play guitar, mostly fingerpicking. currently working through tabbing out all of sufjan stevens' michigan album. 

**video games:** bg3 ruined my life. [come play slay the spire 2 with me](https://steamcommunity.com/id/wyllstarion/)!

**ttrpgs:** i play a lot of dnd for someone who shills pathfinder 2e as much as i do. 

---

## let's connect _!_

find me on [LinkedIn](https://www.linkedin.com/in/ayanapatidar/)!
