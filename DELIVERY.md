# DELIVERY — Presentazione Codiasco @ ALM 2026 (build v1 · 21/07/2026)

> Appendice unica del pacchetto (decisione 9/9 approvata da Paulo, sessione `PKM-cowork-fable5-20260721-1423-d469`). File: `index.html` — autonomo, offline-first, pronto per GitHub Pages (repo → Settings → Pages → deploy from branch; nessuna build necessaria).

## 1. Contenuto del pacchetto

| File | Cosa |
|---|---|
| `index.html` | Le **due pile speculari** EN/FR in un solo file (toggle EN/FR nell'HUD o tasto `L`), 12 slide, note del relatore integrate (tasto `N`), timer (target 18,5' con allarme), versione statica (tasto `F`) e stampa/PDF (tasto `P`). Nessuna dipendenza esterna: funziona **senza connessione**. |
| `DELIVERY.md` | Questo documento. |

**Comandi:** `←/→` o click = slide · `L` lingua · `N` note relatore · `T` timer · `F` vista statica (scroll) · `P` stampa/PDF (fallback offline distribuibile).

## 2. Decisioni di design prese (handoff 21/07, 9 approvazioni di Paulo)

1. **Titoli-conclusione** su tutte le 12 slide (benchmark Economist/Graphic Detail come disciplina, GRA-2 del manuale).
2. **Schermo minimo**: 60–70% visuale; contenuto completo nelle note del relatore.
3. **5 famiglie visive**: A identità (1,2,8) · B dati (3,4,6) · C tempo/livelli (5,9) · D progetti (7,10,11) · E chiusura (12). "Sandwich tonale" PRE-1: apertura e chiusura su fondo scuro.
4. Slide 4: **iceberg** dominante; numero-guida **€478M Piemonte**; globali come contesto.
5. Slide 5: **timeline editoriale**, 4 tappe maggiori (2020 · 2023 · 2024–25 · 2026), avanzamento automatico 20 s con pausa/frecce + fallback statico.
6. Slide 9: **niente piramide** — stessa grammatica del Plural Path Map, trio accordo·progetto·risultato per livello.
7. Slide 11: **Caffè dell'Acre principale**, Storie da Asporto e TUAS complementari.
8. Slide 12: **CTA dominante** (desk · live agosto · QR · contatto); sfide/pratiche in banda secondaria + voce.
9. Pacchetto completo (questo documento).

## 3. Conformità al Design System Codiasco

- **Colori:** solo token confermati 11/07/2026 (`#363636` nero · `#3d8e42` verde · `#ce1c1e` rosso · `#cbcbcb` grigio · `#ffffff`). Verde = titoli/accенto/dati (COL-4); rosso = enfasi puntuale; corpo di testo sempre nero/bianco (COL-3); accenti mai sul grigio; max 3 colori per slide. Unico derivato: `#f4f4f4` (fondo sottile, dal grigio) e `#7fc784`/`#ff6b6b` (schiariture di verde/rosso SOLO su fondo scuro per contrasto WCAG — da ratificare o sostituire).
- **Tipografia:** Inter (TIP-1, segnaposto confermato) con fallback Helvetica/Arial; numeri tabellari (TIP-3) sugli indicatori.
- **Logo:** orizzontale **negativo** su fondi scuri, **positivo** su fondi chiari (LOGO-6); area di rispetto e dimensioni min ok.
- **Grafici:** titolo = frase-risultato (GRA-2); etichette dirette, niente legende flottanti (GRA-3); leggibile in scala di grigi (verde vs grigio = contrasto di luminosità).
- **Foto:** FOTO-1/2/3/4 rispettate nei placeholder (stile documentale, liberatoria, anti-stereotipo, velo per testo su foto).

## 4. Fonti dei dati

| Dato | Fonte | Stato |
|---|---|---|
| Rimesse Piemonte €478 mln / Torino €263 mln (2025) | Banca d'Italia via Torino Oggi, 24/05/2026 | confermato |
| Rimesse globali US$685 mld (2024) | World Bank–KNOMAD | confermato |
| Torino: 16,1% stranieri · 21% imprese migrant-led (vs 12% Italia) · 19,4% assunzioni 2024 | Dossier Statistico Immigrazione / CCIAA via ANSA, 12/2025 | confermato |
| Fondazione 09/10/2020, 9 fondatrici, 20 aderenti | Atto costitutivo + libro soci (cofre Codiasco) | confermato |
| TILILA (Oxfam/AICS, Marrakech 27/07) | Accordo 02/2025 + conferma Amajou 20/07 | confermato |
| L. 125/2014 art. 26 | Normattiva | confermato |

## 5. Inventario dei dati NON confermati (⚠ prima dell'uso pubblico)

1. **"5+ accordi firmati"** (slider slide 2) — contare gli accordi effettivi (CSA, Comune, Città Metro, Oxfam, TUAS…): `[da confermare]`.
2. **"12+ comunità"** — conteggio esatto dalle 20 aderenti: `[da confermare]`.
3. **Stadio attuale Caffè dell'Acre** (slide 11) — conferma di Paulo.
4. Città Metropolitana: progetto/risultato del livello 3 (slide 2 e 9) — `[in definizione]`.
5. Numeri PerMicro citati nelle note — allineare con il loro stand al Knowledge Fair.

## 6. Placeholder pendenti

1. **Plural Path Map**: i dati sono nel blocco `PPM_DATA` (inizio dello script) marcato `_placeholder:true` — **sostituire con il JSON ufficiale di Paulo** mantenendo la struttura territorio→presenza→progetti/partner→indicatori→evidenza.
2. **Fotografie** (slide 1, 8, 10, 11): riquadri tratteggiati con specifica; raccolta presso le aderenti con liberatoria (priorità Marocco, Senegal, Albania, Perù, Nigeria).
3. **QR code** (slide 12): generare quando esiste il link del modulo contatti.
4. **Font Inter**: il file usa il fallback di sistema; per fedeltà totale offline incorporare i WOFF2 (≈100 KB) o installare Inter sul portatile dello stand.
5. **Marchio Terra Madre Off**: formula prudente «nel quadro di» — aggiornare dopo la risposta di Antonio Puzzi sull'uso di logo/marchi Slow Food.

## 7. Crediti immagini

Nessuna immagine di terzi inclusa nella build v1 (solo placeholder + logo Codiasco, vettoriale ufficiale 13/07/2026). Da compilare quando le foto entrano.

## 8. Verifica finale (checklist handoff §14) — stato build v1

Chiarezza ✅ (titolo-conclusione, test 5 secondi) · Evidenza ✅ (fonti in ogni slide dati) · Gerarchia ✅ (un elemento dominante per slide) · Identità ✅ (solo DS Codiasco; benchmark tradotto, non copiato) · Presentazione orale ✅ (note integrate, durate) · Robustezza ✅ (offline, fallback statici, funziona senza animazioni). **Residuo:** rivedere su schermo reale dello stand (proiettore/TV) prima di giovedì — PRE-3.
