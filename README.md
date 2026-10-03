# Research Protocol Deviation Tracker

Check deviation records for protocol version, impact assessment, and review owner.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-research-protocol-deviation-tracker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
