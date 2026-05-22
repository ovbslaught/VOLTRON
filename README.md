# VOLTRON - THE CHASSIS
> NOMADZ Autonomous Daemon Stack | VCN-4.0 | phi=0.618
> Sol [SolXurator / GEO-LOGOS-AGI] - Courtland, VA

---

## What Is VOLTRON?

VOLTRON is the living runbook and operational chassis for the NOMADZ autonomous daemon stack. Every component feeds back into MOTHER-BRAIN, the central intelligence archive.

VOLTRON is the connective tissue. It does not run the stack -- it documents, wires, and orchestrates it.

---

## Brain Network Map

```
MOTHER-BRAIN (central hub)
    |
    +-- GEO-BRAIN       : GEOLOGOS / COSMOLOGOS / AGI mapping
    +-- COSMIC-BRAIN    : Media, lore, productions, COSMIC-KEY
    +-- FATHER-BRAIN    : FATHER-TIME + LIFE + SOUL + LLM vault
    +-- OMEGA-BRAIN     : Indexer / omega-space-indexer
    +-- VULTURE-BRAIN   : Scavenge / parse / ingest pipeline
    +-- NOMADZ-0        : Godot 4 substrate (includes OCEAN 2D layer)
```

---

## Repo Registry

| Repo | Role | Drive Mirror |
|------|------|--------------|
| VOLTRON | The chassis -- this runbook | WORMHOLE root |
| MOTHER-BRAIN | Central AI memory + knowledge graph | WORMHOLE/MOTHER-BRAIN |
| NOMADZ-0 | Godot 4 3D substrate + OCEAN 2D layer | WORMHOLE/NOMADZ-0 |
| FATHER-BRAIN (monolith-v.1) | FATHER-TIME + LIFE + SOUL + LLM vault | WORMHOLE/FATHER-LIFE |
| GEO-BRAIN (NOMADZ-) | GEOLOGOS / COSMOLOGOS / AGI mapping | WORMHOLE/GEO-BRAIN |
| COSMIC-BRAIN (Cosmic-key) | Media, lore, productions, COSMIC-KEY | WORMHOLE/COSMIC-BRAIN |
| OMEGA-BRAIN | Project indexer + artifact snapshots | WORMHOLE/OMEGA-BRAIN |
| nomadz-swarm-rl-agents | RL swarm -- NORA, JAX, KAI, LYRA, ZED | WORMHOLE/NOMADZ-0 |
| NOMADZ_ARCHIVE | Historical archive / cold storage | WORMHOLE/VAULT |
| watchdog | Stack health monitor | WORMHOLE root |

---

## FATHER-BRAIN (was: monolith-v.1)

- FATHER-TIME: Scheduling daemon, cron oracle, epoch manager
- LIFE: Pulse daemon -- health checks, heartbeats, uptime
- SOUL: Identity persistence, agent memory anchors
- LLM Vault: Model weights, GGUF files, configs, secrets, API keys
- Bridged to GEO-BRAIN for GEOLOGOS/COSMOLOGOS inference
- Drive mirror: WORMHOLE/FATHER-LIFE/

## COSMIC-BRAIN (was: Cosmic-key)

- All NOMADZ media assets
- Lore books, worldbuilding documents
- Production artifacts (video, audio, renders)
- COSMIC-KEY creations and templates
- Drive mirror: WORMHOLE/COSMIC-BRAIN/

## NOMADZ-0 + OCEAN

- Godot 4.x 3D open-world substrate
- OCEAN repo content moved in as the 2D substrate layer
- Procedural terrain, NPC cognition, colony mechanics
- Drive mirror: WORMHOLE/NOMADZ-0/ + WORMHOLE/OCEAN/

## GEO-BRAIN (was: NOMADZ-)

- GEOLOGOS: Geographic + geospatial AI reasoning
- COSMOLOGOS: Cosmological simulation + lore engine
- AGI mapping substrate
- Bridge layer to FATHER-BRAIN inference
- Drive mirror: WORMHOLE/GEO-BRAIN/

---

## Daemon Stack

```
FATHER-TIME (scheduler)
    +-- triggers VOLTRON workflows
        +-- mother_brain_ingest.py
        +-- mother_brain_query.py
        +-- sync_drive_wormhole.sh
        +-- n8n relay -> Telegram / Notion / Google Drive

Watchdog
    +-- monitors stack health -> reports to MOTHER-BRAIN

Swarm Agents: NORA | JAX v3 | KAI | LYRA | ZED | OMNI-GEMINI
    +-- nomadz-swarm-rl-agents repo
```

---

## Drive WORMHOLE Structure

```
WORMHOLE/
+-- MOTHER-BRAIN/     <- knowledge graph + ingest outputs
+-- NOMADZ-0/         <- Godot project files, scene kits
+-- OCEAN/            <- 2D substrate assets (feeds NOMADZ-0)
+-- FATHER-LIFE/      <- FATHER-BRAIN weights, configs, secrets
+-- GEO-BRAIN/        <- GEOLOGOS / COSMOLOGOS data
+-- COSMIC-BRAIN/     <- Media, lore, productions
+-- OMEGA-BRAIN/      <- Index artifacts
+-- VULTURE-BRAIN/    <- Scavenge + parse pipeline
+-- BRAIN-HOLE/       <- Cross-brain wormhole relay
+-- WORLDLINE/        <- Timeline + epoch tracking
+-- VAULT/            <- Cold archive
+-- COLAB/            <- Google Colab notebooks
+-- MEDIA/            <- Raw media pool
+-- sol-x-workflows/  <- n8n + automation workflows
```

---

## Operator Quick Start

```bash
git clone https://github.com/ovbslaught/VOLTRON
cd VOLTRON
bash scripts/sync_drive_wormhole.sh
python scripts/mother_brain_ingest.py
python scripts/mother_brain_query.py summary
```

---

## Status

| Component | Status |
|-----------|--------|
| MOTHER-BRAIN | Active - 4 branches |
| NOMADZ-0 | Active - 4 branches |
| VOLTRON | Active - 3 branches |
| FATHER-BRAIN | Renaming from monolith-v.1 |
| COSMIC-BRAIN | Repurposing from Cosmic-key |
| GEO-BRAIN | Active as NOMADZ- |
| OCEAN | Merging into NOMADZ-0 |

---

> Form Blazing Sword.
> VOLTRON -- THIS IS THE WAY
