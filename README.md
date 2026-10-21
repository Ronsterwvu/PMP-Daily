# PMP Daily

A single-page PMP exam practice app: a daily 60-minute study plan, scenario-based questions across the People, Process and Business Environment domains, a study streak and readiness tracking.

Originally built as a claude.ai artifact: https://claude.ai/artifact/7BAPHkiLq4fZjFBzn4kMKn

## Running it

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Behavior outside claude.ai

- Progress is saved in the browser's `localStorage`. The cross-device account sync only works inside the claude.ai artifact.
- The AI-generated drills need the claude.ai runtime and are unavailable when the file is opened on its own. The built-in question bank works everywhere.
