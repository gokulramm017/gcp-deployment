                 Google Cloud Project
                         │
                         ▼
                ┌─────────────────┐
                │  Compute Engine │
                │                 │
                │ e2-standard-8   │
                │ 8 vCPU          │
                │ 32 GB RAM       │
                │                 │
                │ Ubuntu 22.04    │
                └───────┬─────────┘
                        │
             ┌──────────┴──────────┐
             │                     │
             ▼                     ▼
       Boot Disk               Data Disk
       100 GB                  500 GB
       pd-standard             pd-standard
       /                       /data