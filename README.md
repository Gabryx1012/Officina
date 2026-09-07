# Officina

Un assistente AI locale per Windows, con portale di chat, strumenti di coding e Ollama.

## Scarica e avvia

1. Apri [Releases](https://github.com/Gabryx1012/Officina/releases) e scarica **Officina-GitHub.zip**.
2. Estrai tutta la cartella.
3. Fai doppio clic su **AVVIA-OFFICINA.cmd**.

Il launcher prepara Node.js e Ollama portatili se mancanti e scarica il modello previsto dal profilo RAM. Internet è necessario al primo download; l’inferenza gira sul computer. Sono inclusi i launcher per Windows 10/11 a 64 bit e il sorgente completo dell’applicazione.

## Cosa include

- Chat in italiano e cronologia locale.
- Agente con piani fino a sei file, revisione, backup e anteprima HTML.
- Console per comandi singoli e client da terminale.
- Strumenti Windows UI Automation con azioni da approvare.
- Profili RAM da 8 GB e catalogo di modelli locali.
- README completo, architettura, test e rapporto di validazione nel pacchetto.

## Limiti verificati

17 test automatici superati su Node 22/24. Il controllo desktop è stato provato sulla Calcolatrice. I modelli locali possono produrre codice errato: nel collaudo alcune correzioni hanno richiesto intervento esterno. Officina non replica Astra e non controlla tutte le applicazioni Windows. I profili 8/16 GB non sono stati collaudati su macchine fisiche di quelle taglie.

Il pacchetto include il sorgente sotto licenza MIT. I modelli e i runtime hanno le proprie licenze e vengono scaricati separatamente. Configurazioni personali, log, backup e workspace sono esclusi.
