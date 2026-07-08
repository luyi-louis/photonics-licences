# Photonics Suite — revocation list

This file lists **revoked licence IDs** for the Photonics Suite. The app fetches it
at startup (fail-open) and returns to limited mode if its licence ID is listed.
Only opaque IDs live here — no personal data.

```json
{ "revoked": ["licenceId1", "licenceId2"] }
```
