# Chinese Reader — Vocabulary-Constrained Stories

Open `index.html`. Choose among five stories. No inline pinyin; tap a word to see pronunciation, meaning, a **separate** dictionary example, and grammar help.

The three balanced stories and two late-vocabulary reinforcement stories are generation choices, **not** controls or labels shown to the reader.

The rewritten stories are checked by `validate_stories.py` against the Anki vocabulary. The maximum is **five distinct non-Anki words per story** (not five occurrences). Any introduced words are supplemental dictionary entries with independent example sentences. See `validation_report.json` for the actual count per story.

To update a GitHub Pages deployment, replace `stories.js`, `vocabulary.js`, and `explanations.js`; replacing all files is fine too.
