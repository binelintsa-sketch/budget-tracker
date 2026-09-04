# Sources & AI Disclosure

## AI usage

We used ChatGPT to help with project setup and wording:

- Structure and wording of `README.md` (layout, how to run, team workflow)
- Drafting other markdown helpers (this disclosure note and related docs)
- Small **self-check blocks** at the bottom of `data_store.py`,
  `validation.py`, `processing.py`, and `reports.py`
  (`if __name__ == "__main__"`) so each person can run their file and see
  PASS/FAIL before opening a PR

Those self-checks are not part of the app menu.

The actual function bodies (the `# TODO` logic for load/save, validation,
processing, and reports) are written by the team member who owns that file.

## Reference (APA 7th)

OpenAI. (2026). *ChatGPT* [Large language model].
https://chatgpt.com
