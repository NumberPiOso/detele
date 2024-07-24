---
name: Automated - Drop tables not updated
about: >
    This template is used by the github action clean-stale-models to create
    issues.
title: {{ env.env }} - Drop tables not updated - {{ date | date('dd MMM') }}
labels: housekeeping
---

This github issue is created automatically by clean-stale-models actions.

{{ env.MESSAGE }}
