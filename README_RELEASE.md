# XGen NR Kenya Fusion³ — Planetary Stewardship v2.2

Canonical source package matching the verified live Vercel/Supabase release.

## Live runtime
- Vercel: https://xgen-nr-kenya-live.vercel.app
- Supabase Edge: `nr-kenya-live-v2`
- API: `2.2`
- Protocol: `DAVL_PLANETARY_STEWARDSHIP_v2.2.0`

## Evidence boundary
`UNKNOWN != 0` · `INFERENCE != MEASUREMENT` · causal attribution is not automatic · human authorization is required.

## Verification
```bash
python scripts/verify_release.py
```

The web manifest is the same integrity envelope used by the live dashboard. The source manifest additionally covers repository-only source and CI files.
