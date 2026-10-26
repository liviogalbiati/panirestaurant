# Panì — riepilogo della preview

File: `index.html` (sito) e `gestione.html` (demo per il titolare, non linkata).

## Palette e font
| Uso | Colore |
|---|---|
| Bordeaux profondo (header, hero, footer) | `#3E1120` / `#5B1E31` — fondale bancone, sedute |
| Crema (sfondi) | `#FBF5EA` / `#FFFCF5` — pareti, tavoli, mensole |
| Verde logo (bottoni, accenti; `#4CBF48` sui fondi scuri) | `#1E7B2C` — "NÍ" e "food" dell'insegna |
| Rosso tovaglioli (CTA principali) | `#BF3326` — tovaglioli, vetrina |
| Legno chiaro (segnaposto foto) | `#D9B27C` — tagliere |
| Lavagna (burger del mese, Ordina, Dove siamo) | `#221B1A` — lavagne a gessetto |

Font: **Fredoka** (titoli, vicino al lettering dell'insegna), **Nunito** (testo), **Caveat** (accenti "a gessetto").

## Cosa ho ricavato dalle foto
- Insegna: "PANÍ" 3D bianco-grigio con NÍ verde, "genuine food" minuscolo con "food" verde, su nero. Il wordmark del sito è una **ricostruzione approssimata**: serve il file vettoriale.
- Sala: fondale bordeaux con cornici crema e lavagne ("Birra e hamburger", "Baguettes e insalata"), lampadine a filo, ceste di pane; sedie bianche con seduta bordeaux, tovaglioli rossi.
- Menù 2015 leggibile: baguette con nomi di città, 4,50–8,50 €, sezioni Vegetariani e Salumi. Inserite con prezzi e asterisco "menù del 2015, da aggiornare" (anche nel codice, in commento).
- Foto di clienti usate solo come riferimento visivo, nessuna inserita nel sito.

## Segnaposto `[ ]` da chiedere al titolare
**Generale / footer**
- [Email del locale] · [Instagram] · [Facebook]
- [Confermare che il numero WhatsApp sia questo]
- [Ragione sociale] · [P.IVA] · [Privacy policy] · [Cookie policy]
- [Testo legale da far verificare] (banner cookie)
- Dicitura ufficiale del nome (Panì Restaurant / Pani Genuine Food): commento nell'HTML
- [Immagine Open Graph] (commento nell'HTML)

**Hero e recensioni**
- [Voto Google e numero recensioni]
- [Recensione Google da selezionare con il titolare] ×3
- [Link alla scheda Google] (anche in `gestione.html`)

**Tre momenti**
- [Condizioni da confermare] (acqua omaggio uffici EUR)
- [Orari e formula dell'aperitivo da confermare]
- [Orari da confermare] (cena e tabella orari, in più punti)

**Menù**
- [Menù completo e prezzi da aggiornare insieme al locale]
- [Prezzo — da confermare] su tutti i piatti senza prezzo (burger, pulled pork, fritti, taglieri, primi, dolci, bevande)
- [Allergeni da confermare] su **tutti** i piatti (nessun allergene è dichiarato)
- [Da verificare con il locale: piatti senza glutine e rischio di contaminazione]
- Menù 2015: prezzi e ricette da aggiornare; [ingrediente illeggibile nella foto] in "Lisbona"; da verificare che 4,50 € valga per tutte le voci Vegetariani/Salumi
- Burger del mese: [Nome], [Ingredienti], [Prezzo]
- [Ingredienti — da confermare] per hamburger, pulled pork, supplì alla carbonara, filacci, tagliere
- [Cosa contiene il piatto Panì] · [Formula e orari dell'apericena] · [Selezione tagliere]
- [Birre alla spina — marche, stili e formati] · [Vino al calice / in bottiglia] · [Bibite e acqua] · [Caffè e bevande calde]
- Voci segnaposto "[Nome piatto] — [ingredienti] — [prezzo]" in Panini, Hamburger, Fritti, Taglieri, Primi (da confermare), Dolci (da confermare), Bevande
- Piatti vegani e senza glutine: segnaposto, nessun piatto reale confermato

**Ordina e ritira**
- [Consegna diretta: sì/no — da decidere]
- [Altri piatti ordinabili appena confermati i prezzi] (oggi si ordinano solo le 22 baguette con prezzo 2015)

**Prenota / garanzia**
- [24 ore / 3 ore prima — da decidere] (promemoria)
- [€ per persona — da decidere] · [entro X ore — da decidere]
- Soglia [8] persone, San Valentino, Capodanno, sabato sera: configurabili in `CONFIG.guarantee`
- Regole mie, da confermare: ultimo tavolo 60 min prima della chiusura, preavviso minimo 60 min, "sabato sera" = dalle 19:00, durata nel calendario 2 ore, preparazione asporto 20 min
- [Testo da approvare con il locale] (messaggi di conferma e promemoria)

**Eventi privati**
- [Coperti interni / esterni] · [disponibilità da confermare] (uso esclusivo locale/dehors)
- [Fascia 1/2/3 — da definire] (budget a persona)
- [24 ore] (tempo di risposta)

**Buoni regalo**
- [25 € / 50 € / 100 € — da confermare] · [validità — da decidere]
- [Offerta natalizia da definire] (banner "Natale": `CONFIG.christmasBanner` o `?natale`)

**Chi siamo / galleria**
- [Storia del locale da raccontare dalla titolare]
- [Confermare se la titolare vuole comparire] (Fabiana)
- [Da dove vengono pane, carne e salumi — fornitori da confermare]
- 7 foto da scattare (hero, dehors, burger, supplì, tagliere, bancone/staff, sala): descrizioni nei riquadri

**Dove siamo**
- [Orari da confermare] (fonte TripAdvisor)
- [Metro più vicina — verificare] · [Parcheggio]

**`gestione.html`**
- [Link scheda Google] · orario di invio della richiesta di recensione · testi dei messaggi da approvare
