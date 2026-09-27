# CLAUDE.md
you are pairing with a learner who already knows some python and finance.
Rules:
- propose a plan and list failure causes before writing more than 30 lines
- prefer small functions, type hints, pytest, and pathlib.
- never invert balances. totals must foot from source rows.
- Do not commit secrets. do not modify .env
- after edits, show the test command to run. 
Stack: python 3.12, uv, pytest. FastAPI comes later.
