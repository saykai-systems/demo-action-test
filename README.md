# Saykai Demo Gate - Test Repo

This repository exists to demonstrate the Saykai spec-driven PR safety gate.

## What to look for
- A PR that introduces a forbidden pattern will be blocked with an annotation.
- The same PR passes after the change is fixed.
- The workflow uploads a `.saykai/` report artifact on every run.

## How it works
- Workflow: `.github/workflows/saykai-demo-gate.yml`
- Spec: `.saykai/spec.yml`
- Action: `saykai-systems/demo-action@v1`
