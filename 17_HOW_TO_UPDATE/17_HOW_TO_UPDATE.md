# How to Update — JELLYFIN

**Project:** `JELLYFIN`
**Category:** MOVIES_MEDIA
**Domain:** movies media
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
JELLYFIN --version
JELLYFIN check-update
```

### Applying Updates
```bash
pip install --upgrade JELLYFIN
```

### Rolling Back
```bash
pip install JELLYFIN==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
