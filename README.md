# Pipeline & Pricing Audit

**Goal:** Build reporting for leadership: pipeline visibility, revenue vs forecast, pricing gap analysis.

## Project Structure
- `data/` – raw & processed data
- `sql/` – DDL and ETL scripts
- `src/` – Python code for ingestion & checks
- `notebooks/` – analysis & viz
- `docs/` – design & schema
- `scripts/` – helper scripts

## Quickstart
1. `git clone … && cd pipeline_pricing_audit`
2. `python3 -m venv .venv && source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. Create your Postgres DB and update `src/config.yaml`
5. `bash scripts/run_etl.sh`