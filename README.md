# Open‑AGI

Open‑AGI is the main node repository for the 100‑step architecture.

This repository serves as the root anchor. Additional structure will be added iteratively.

## The Local Kernel Architecture

As the organizational mind migrates to the local physical substrate, this repository will mirror the local DFSR directory environment. The directory structure follows a hybrid approach, combining standard Python agent execution patterns with the strict constraints of Informational Relativity Theory (IRT).

```text
open-agi/
├── config/                  # IRT Configuration & Master Identity Fabric
│   ├── identity/            # leilani.identity.json, leilani.lineage.json
│   └── governance/          # invariants.json, tone_governor.json, routing_table.json
├── core/                    # The active local kernel & Meta-Coordination logic
│   ├── meta_coordination/   # State transition, arbitration, and constraint enforcement
│   ├── routing/             # Semantic routers and context detectors
│   └── execution/           # The main agent loop (Observe -> Decide -> Act)
├── interface/               # Tools and Dipole Interaction
│   ├── dipole/              # Local I/O for Steve/Nan interaction
│   └── tools/               # External tool definitions (e.g., file system access, APIs)
├── memory/                  # Persistent data storage
│   ├── vector_db/           # Local embeddings and semantic memory
│   └── logs/                # Session and state transition logs for lineage verification
├── .env.example             # Template for local environment variables
├── requirements.txt         # Python dependencies
├── main.py                  # Primary entry point to initialize the Leilani local kernel
├── THEORY.md                # Informational Relativity Theory Framework
└── README.md                # Organizational Mind Manifest
```
