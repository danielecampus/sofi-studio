# sofi-studio

Materiale di studio per Sofia.

🌐 **Sito:** https://danielecampus.github.io/sofi-studio/ — la home (`index.html`) raccoglie tutte le dashboard e i PDF.

## 🎓 inglese/Advanced/ (livello C1–C2)

| File | Cosa contiene |
|------|---------------|
| [advanced-dashboard-C1-C2.html](inglese/Advanced/advanced-dashboard-C1-C2.html) | 🎓 **English Dashboard Advanced** — app C1–C2: grammatica avanzata (8 schede con quiz), lessico/flashcard, word formation, registro, idioms, **esercizi misti** e un **test finale cronometrato da 60 minuti** (40 domande, 5 sezioni). |
| [advanced-grammar-C1-C2.pdf](inglese/Advanced/advanced-grammar-C1-C2.pdf) | 📐 Glossario di grammatica avanzata e formale: condizionali, inversione, congiuntivo, cleft, participiali, passivo, modalità, connettori. |
| [idiomatic-expressions.pdf](inglese/Advanced/idiomatic-expressions.pdf) | 🎭 30 idiomatic expressions con significato e 2 esempi. |
| [phrasal-verbs-C1-C2.pdf](inglese/Advanced/phrasal-verbs-C1-C2.pdf) | 🔗 60 phrasal verbs C1→C2 su 4 livelli. |

## 📁 inglese/

Cartella con tutto il materiale di inglese (Prima Liceo — Verso il B1).

| File | Cosa contiene |
|------|---------------|
| [english-dashboard.html](inglese/english-dashboard.html) | App di ripasso **base** (Present Simple/Continuous, Past Simple, Future, Modals, Articoli) con quiz, flashcard, verbi e mini test. |
| [english-dashboard-2.html](inglese/english-dashboard-2.html) | 🚀 **English Booster** — nuova app **avanzata** basata sull'indice del libro: 9 capitoli di grammatica, ~120 vocaboli, verbi irregolari estesi + trainer, esercizi extra e un **Test Finale in 3 sezioni** (Grammatica, Vocabolario, Comprensione del testo). |
| [riassunto-grammatica.pdf](inglese/riassunto-grammatica.pdf) | 📄 Riassunto stampabile con **regole ed esempi** dei 9 capitoli di grammatica (generato da `riassunto-grammatica.html`). |
| [riassunto-grammatica.html](inglese/riassunto-grammatica.html) | Sorgente A4 del riassunto (rigenera il PDF con Chrome/Edge headless). |
| [phrasal-verbs-C1-C2.pdf](inglese/phrasal-verbs-C1-C2.pdf) | 🇬🇧 **British Phrasal Verbs (C1 → C2)** — glossario avanzato: 60 phrasal verbs in 4 livelli (da base a idiomatici) con spiegazione in inglese e 2 esempi ciascuno. |
| [phrasal-verbs-C1-C2.html](inglese/phrasal-verbs-C1-C2.html) | Sorgente A4 del glossario phrasal verbs. |
| [inglese_programma_1liceo.pdf](inglese/inglese_programma_1liceo.pdf) | Indice del programma del libro di testo (le 12 unità). |

### Come si usa
- Apri i file `.html` con un doppio clic (si aprono nel browser, funzionano offline).
- Nella app, l'area **📊 Risultati** è protetta da password (predefinita: `daniele2026`, modificabile in cima al codice) e permette di copiare un riepilogo da inviare su WhatsApp.

### Rigenerare il PDF del riassunto
```bash
chrome --headless=new --disable-gpu --no-pdf-header-footer \
  --print-to-pdf="inglese/riassunto-grammatica.pdf" \
  "inglese/riassunto-grammatica.html"
```
