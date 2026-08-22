# CUAD Contract Review & Risk Flagging Pipeline

Ingests CUAD contracts, extracts labeled clauses, compares them to a legal playbook, flags risk, and writes an audit log.

Agent policy: see `CLAUDE.md` and `AGENTS.md`.

```bash
pip install -r requirements.txt
pytest tests/ -v
python main.py --first
```
