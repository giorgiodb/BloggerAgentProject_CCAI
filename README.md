# 🧵 BloggerAgent — L'Agente Intelligente per Blog Creativi

**BloggerAgent** è un assistente basato su AI progettato per aiutare blogger e content creator nel campo delle guide pratiche "how-to". Automatizza il flusso di creazione dei contenuti: dalla generazione di idee alla scrittura della bozza, fino alla pianificazione editoriale.

> Costruito con [LangGraph](https://github.com/langchain-ai/langgraph), Tavily Search, OpenAI e Python, questo agente sfrutta le capacità dei Large Language Model (LLM) per assisterti nella gestione del tuo blog.

---

## ✨ Funzionalità principali

- ✅ **Suggerimento di argomenti** originali e coerenti con i post precedenti
- 🌐 **Ricerca online** con selezione automatica delle fonti (via Tavily)
- 📝 **Generazione automatica di bozze** per nuovi articoli
- 📅 **Pianificazione editoriale** di serie tematiche
- 💡 **Proposte future** basate sulla cronologia dei post
- 🖼️ **Editor GUI (opzionale)** per rivedere e salvare le bozze con `gradio`

---

## 🔄 Workflow dell’agente

Il sistema segue un flusso di lavoro guidato che combina automazione intelligente e controllo umano. Una volta avviato, l’utente interagisce con un menu testuale che permette di scegliere tra diverse azioni: 
- generare un nuovo post
- modificare bozze esistenti
- ricevere suggerimenti per futuri contenuti
- pianificare una serie tematica.

Se si sceglie di generare un nuovo post, l’agente propone un argomento coerente con i post precedenti oppure completamente nuovo. L’utente può accettare la proposta o chiedere alternative.

Successivamente, l’agente effettua una ricerca online utilizzando Tavily e presenta una lista di fonti attendibili. Una volta approvate le fonti e fornite tramite LLM, l’agente elabora una bozza strutturata del contenuto, che può essere salvata direttamente oppure revisionata tramite un editor grafico opzionale integrato nel sistema. 

Questa flessibilità consente di mantenere il controllo editoriale, pur velocizzando la fase creativa.

Infine, la bozza può essere schedulata nel calendario editoriale, specificando una data futura di pubblicazione. In alternativa, l’agente è in grado di generare una serie di post legati tra loro, programmando automaticamente titoli e date coerenti all’interno di un piano editoriale più ampio. Dopo ogni pubblicazione o pianificazione, l’agente aggiorna la propria memoria per evitare ripetizioni e per suggerire contenuti futuri sempre più mirati e originali.

![output](https://github.com/user-attachments/assets/c6a58570-bdd7-4754-bbff-cc4e4d91a72e)

## 📦 Installazione

Assicurati di avere Python 3.9+ e installa i pacchetti necessari prima di eseguire l'avvio


