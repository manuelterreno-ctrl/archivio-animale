## 1. Identità del Vault

Il Vault _Animali_ è un **ecosistema narrativo-ecologico**, non un archivio zoologico.  
Serve a raccogliere, organizzare e trasformare conoscenze scientifiche sugli animali in **materia narrativa**.

Ogni nota è una forma di vita reale: osservata, percepita e restituita nel suo modo di stare al mondo.  
Lo scopo non è classificare, ma **capire e raccontare** — per costruire racconti e personaggi animali non antropomorfi,  
che incarnino tensioni, relazioni e sensibilità proprie del vivente.

---
## 2. Principi generali

1. **Accumulazione per specie o gruppo**  
    Ogni informazione proveniente da una fonte confluisce direttamente nella nota dedicata alla specie, al genere, alla famiglia, all’ordine o alla classe.
    
2. **Fonti come nutrimento, non archivio**  
    Le fonti non hanno una cartella propria.  
    Le informazioni derivanti da esse vengono inserite direttamente nei frammenti delle note tassonomiche, con il riferimento locale alla fonte.
    
3. **Scrittura libera, non schematica**  
    Le note crescono organicamente: i frammenti si aggiungono nel tempo, separati da `---`, come un diario di ricerca e scoperta.
    
4. **Tag semantici, non tassonomici**  
    I tag non servono per classificare, ma per collegare concetti, comportamenti, sensi, ecologie e relazioni, in vista di future ricerche incrociate.
    
5. **Struttura leggera e scalabile**  
    La base del sistema è fatta di **cartelle + link + tag coerenti**.  
    Dataview e YAML complessi sono opzionali e introdotti solo se portano reale vantaggio.
    
6. **Ecologia come drammaturgia**  
    Le relazioni ecologiche (predazione, mutualismo, simbiosi, competizione, ecc.) sono interpretate come **forme narrative**: forze di attrazione, conflitto, dipendenza o cooperazione.

---

## 3. Struttura delle cartelle

Animali/
├─ Tassonomia/
│  ├─ Classe/
│  ├─ Ordine/
│  ├─ Famiglia/
│  ├─ Genere/
│  └─ Specie/
├─ Temi Trasversali/
│  ├─ Ecologia/
   ├─ Comunicazione/
│  ├─ Sensi/
│  ├─ Comportamenti/
│  ├─ Habitat/
│  └─ Riproduzione/
└─ Relazioni Ecologiche/
   ├─ Predazione.md
   ├─ Mutualismo.md
   ├─ Parassitismo.md
   ├─ Competizione.md
   ├─ Commensalismo.md
   ├─ Simbiosi.md
   ├─ Mimetismo.md
   └─ Facilitazione.md

Ogni cartella ha uno scopo preciso e stabile.  
La tassonomia è la spina dorsale; i temi trasversali sono i nervi;  
le relazioni ecologiche sono i gesti drammatici della vita.

___
## 4. Gerarchia tassonomica minimale

Ogni livello tassonomico punta **solo al livello superiore diretto**.  
Non creare collegamenti multipli o ridondanti.

Esempio:
Specie → Genere → Famiglia → Ordine → Classe → Phylum

_Ogni nota deve linkare solo al superiore diretto _  
Questo mantiene il grafo leggibile, logico e naturale.

___
## 5. Regole di scrittura delle note

---
## 6. Sistema dei tag

### 6.1 Tipologie principali

| Categoria         | Esempi                                                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `#tipo/`          | scimmia, felino, rana, farfalla, formica…                                                                                |
| `#habitat/`       | foresta_pluviale, savana, montagna, fiume…                                                                               |
| `#comportamento/` | notturno, sociale, territoriale, arboreo…                                                                                |
| `#alimentazione/` | carnivoro, frugivoro, insettivoro…                                                                                       |
| `#sensi/`         | vista, udito, olfatto, tatto, ecolocazione, visioneUV…                                                                   |
| `#ecologia/`      | predazione, preda, predatore, mutualismo, simbiosi, competizione, mimetismo, parassitismo, commensalismo, facilitazione… |

### 6.2 Regole d’uso

- In testa alla nota: 2–4 tag identitari.
    
- Nei frammenti: micro-tag locali, anche multipli.
    
- Niente tag tassonomici: i livelli biologici si gestiscono con i link.

---
## 7. Temi Trasversali

I Temi Trasversali non generano contenuto: **raccolgono** e **mettono in relazione** frammenti già presenti nelle specie o nei gruppi.

### Regola di creazione

Crea una nuova nota-tema solo se:

- rappresenta un concetto distintivo e stabile;
    
- è ricorrente in più specie o gruppi;
    
- ha rilevanza narrativa (sensi, percezione, mutualismo, mimetismo…).

---

## 8. Relazioni ecologiche – Drammaturgia naturale

Le relazioni ecologiche sono **forme narrative universali**:  
predazione (conflitto), mutualismo (alleanza), simbiosi (fusione), competizione (rivalità), parassitismo (dipendenza), mimetismo (illusione), commensalismo (convivenza), facilitazione (protezione involontaria).

---
## 9. Ricerca e consultazione

La **ricerca principale** è quella testuale/tag di Obsidian.  
Puoi combinare tag e cartelle per ottenere risultati mirati.

Esempi:
#tipo/farfalla #habitat/foresta_pluviale #comportamento/notturno
→ Farfalle notturne tropicali.

#tipo/felino #habitat/foresta_pluviale #alimentazione/carnivoro
→ Felini carnivori della foresta pluviale.

path:"Tassonomia/Specie" #sensi
→ Tutte le specie con frammenti sui sensi.

Dataview è opzionale, utile solo per panoramiche automatiche nelle note-tema.

---
## 10. Filosofia operativa

1. **Scrivi prima, organizza dopo.**  
    Meglio un frammento grezzo oggi che una scheda perfetta domani.
    
2. **Mantieni leggerezza e coerenza.**  
    Evita YAML e script inutili: il vault deve respirare.
    
3. **Pensa per relazioni.**  
    Ogni link e tag è un filo della rete narrativa.
    
4. **Evita duplicazioni.**  
    I Temi e le Relazioni raccolgono, non riscrivono.
    
5. **La tassonomia è guida, non gabbia.**  
    Ti orienta, ma non ti limita.
    
6. **L’ecologia è drammaturgia.**  
    Ogni relazione tra viventi è una forma di tensione o cooperazione.
---
## 11. Appendice linguistica – Coerenza dei link concettuali

> 🔸 _“Il link va al concetto, non alla parola.”_  
> 🔸 _“Usa sempre la forma generale, singolare e nominale.”_

### Regole

1. I wikilink vanno al **concetto astratto**, non alla forma declinata.  
    ✅ “Usano suoni ultrasonici per la caccia notturna ("ecolocazione").”  
    ❌ “Usano "suoni ultrasonici" per la caccia notturna.”
    
2. Usa forme **singolari e nominali**:  
    _predazione_, _mutualismo_, _territorialità_, _ecolocazione_.
    
3. Evita sinonimi o doppioni concettuali.  
    Usa sempre la stessa parola radice per lo stesso concetto.
    
4. Non creare link su aggettivi o plurali: il link rappresenta il concetto, non la frase.
---
## 12. Evoluzione del sistema

1. Parti solo con **ricerca e tag**.
    
2. Quando serve, crea note-tema o relazioni.
    
3. Aggiungi Dataview solo se il vault lo richiede.
    
4. Quando una specie “matura”, aggiungi una mini-scheda riassuntiva in testa.
---
## 14. Visione finale

> Il Vault _Animali_ è un archivio della vita come intreccio narrativo.
> 
> Ogni specie è un personaggio.  
> Ogni relazione è una scena.  
> Ogni comportamento è un gesto.  
> Ogni senso è una finestra sul mondo.
> 
> Non serve per sapere _tutto_ sugli animali,  
> ma per **imparare a guardarli davvero**.