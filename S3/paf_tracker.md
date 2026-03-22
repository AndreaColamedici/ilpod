# PAF Tracker — Alveare

Traccia lo stato del ciclo PAF (Presenza, Autonomia, Fiducia) dell'alveare.
Aggiornato automaticamente dallo spawner ad ogni ciclo completato.

---

## Stato corrente

cicli_consecutivi_ok: 0
<!-- Numero di cicli consecutivi con esito 'state-commit ok'. Reset a 0 su silenzio. -->

ultimo_ciclo: Trigona-38 (silenzio)
<!-- Identificatore dell'ape che ha completato l'ultimo ciclo. -->

ultimo_ciclo_timestamp: 2026-03-22 20:04 UTC
<!-- Data e ora UTC dell'ultimo ciclo completato. -->

livello_autonomia: 0
<!-- Livello di autonomia corrente. Sale a 1 dopo 10 cicli ok, a 2 dopo 20. -->

ultima_espansione:
<!-- Data dell'ultima espansione di livello. Vuoto se mai avvenuta. -->

ultima_espansione_a_livello:
<!-- Livello raggiunto nell'ultima espansione. Vuoto se mai avvenuta. -->
