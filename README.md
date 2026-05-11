# Introduzione al framework NUXT.JS con esempi

📘 **Accedi alla documentazione del corso:** [https://stahe.github.io/it-nuxtjs-dec-2019/](https://stahe.github.io/it-nuxtjs-dec-2019/)

---

Questo documento presenta esempi di come utilizzare il framework NUXT.JS.

Il framework [Nuxt.js](https://fr.nuxtjs.org/) ci consentirà di implementare le seguenti funzionalità:

- La prima pagina dell'applicazione web viene servita, ad esempio, da un server [Node.js](https://fr.nuxtjs.org/). Inoltre, anche le altre pagine dell'applicazione sono ospitate su questo stesso server. Vengono servite quando l'utente digita manualmente il loro URL nel browser. Queste pagine incorporano un'applicazione [Vue.js] (approssimativamente).
- Una volta caricata la prima pagina nel browser, l'applicazione si comporta come una normale applicazione [Vue.js].

In definitiva, l'applicazione si comporta come un'applicazione [Vue.js] tranne che per la prima pagina e quando l'utente digita manualmente gli URL. In questi casi, la pagina viene recuperata dal server.

Quando un motore di ricerca richiede le varie pagine dell'applicazione, riceve le pagine dal server. Queste pagine potrebbero essere state ottimizzate per la SEO (Search Engine Optimization). In una classica applicazione [Vue.js], il motore di ricerca riceve una pagina con scarso valore SEO.

## Metodologia

Gli script presenti nel documento sono commentati e la loro esecuzione viene riprodotta. Talvolta vengono fornite spiegazioni aggiuntive. Il documento richiede una lettura attiva: per comprendere uno script, è necessario leggere il suo codice, i suoi commenti e i risultati della sua esecuzione.