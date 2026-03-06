# Copilot Instructions for "Python for Everyone"

## 🚀 Project Overview
This repository is a small set of **beginner Python exercise scripts** (e.g., `ex1.py`, `ex12.py`, etc.) intended to teach basic Python concepts (variables, control flow, loops, input/output). There is **no complex architecture** or build system.

## 🧭 Key Patterns / Conventions
- Each file is a standalone script meant to be run directly with `python`.
- The scripts are intentionally simple; they typically only use the Python standard library and `input()` for interactive prompts.
- File names reside in a directory with spaces (`Python for Everyone`), so commands must quote paths (e.g., `"Python for Everyone/ex1.py"`).

## ▶️ How to Run / Verify Changes
Use the system Python interpreter (Python 3) to run a script. Example:

```bash
python "Python for Everyone/ex12.py"
```

If you modify a script, verify that it still runs cleanly and produces the expected output for the example input.

## 🔧 Editing Guidance for Copilot
When suggesting or applying changes:
- Keep changes minimal and educational (these are teaching examples).
- Do **not** introduce new dependencies or frameworks; this repo is pure Python.
- Prefer explicit and clear code over clever/obscure shortcuts.
- Preserve the same style as the rest of the exercises (basic structure, no classes/modules unless necessary).

## 📝 Common “Gotchas” in this Repo
- **Interactive input**: Many scripts use `input()` and expect the user to type values. When running automated checks, you may need to simulate input or refactor into functions.
- **Paths with spaces**: When referencing these scripts from shell commands or CI, wrap paths in quotes.

## 🔎 Where to Look When Making Changes
- `exX.py` scripts in the repo root are the only source files.
- There is no test suite or build process; validation is by running the script and checking output.

---

If anything is unclear in these instructions (e.g., expected behavior for a specific exercise), let me know and I can refine the guidance.