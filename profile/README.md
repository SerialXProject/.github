# SerialXProject

![SerialXProject](https://github.com/SerialXProject/pySerialX/blob/main/banner.png)

## 🚀 Comunicazione Seriale Semplificata e Avanzata per Arduino e Microcontrollori

**SerialXProject** è un progetto in fase di sviluppo che verrà rilasciato completamente nelle prossime settimane in modalità **open-source** sotto **licenza GNU** 🐧.

---

### 🎯 L'obiettivo del progetto

In parole semplici, l'obiettivo è rendere la comunicazione seriale tra dispositivi (in particolare **Arduino** 🔌) molto più **standardizzata** e **semplice da sviluppare**.

Un esempio concreto di utilizzo consiste nello scrivere codice per Arduino **senza dover hardcodare le variabili**, inserendo e modificando i valori reali a runtime tramite uno script in SerialX, oppure utilizzando **Python** 🐍 grazie all'integrazione offerta da **pySerialX**, che espone funzioni Python equivalenti all'esecuzione di codice SerialX.

---

### ⚡ Innovazione ed Efficienza: SerialX_JIT

Per ottimizzare la comunicazione e ridurre drasticamente il carico sugli interpreti, è stato sviluppato **SerialX_JIT**: un linguaggio intermedio ottimizzato per avere un peso notevolmente inferiore su dispositivi con risorse limitate come Arduino 📉.

* **🔄 Esecuzione Just-in-Time:** Questo linguaggio viene interpretato *Just-in-Time* durante la comunicazione.
* **📦 Compattazione:** Consente di compattare le righe SerialX da inviare.
* **🔍 Decoder intelligenti:** Semplifica la lettura delle risposte provenienti dall'altro dispositivo (es. Arduino) grazie a decoder dedicati che rendono il testo facilmente interpretabile ✨.

---

### 🤖 Casi d'uso ideali: Arduino & Raspberry Pi

Un altro scenario di utilizzo eccellente è la comunicazione live tra dispositivi eterogenei, ad esempio tra un **Arduino** e un **Raspberry Pi 5** 🍓. Questo approccio permette di combinare l'affidabilità hardware, la logica a 5V e la reattività in tempo reale di Arduino con la grande potenza di calcolo e le risorse avanzate del Raspberry Pi 💡.
