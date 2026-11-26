# Contributing to PairClear tools

Thank you for helping. These defaults apply to every repo in [github.com/pairclear](https://github.com/pairclear) unless a repo has its own file.

## What helps most

- **Corrections with a source.** If a text about a school of psychology, a technique or a helpline is wrong or outdated, open an issue or a pull request with a link to the source.
- **Translations.** Every tool is English and Russian. Each README's "How to help" section says where the texts live and which build script to run.
- **Verified crisis lines** for more countries (see `not-a-therapist/data/crisis-resources.json`), each with a source link and a check date.
- **Bug reports** with the browser, the language and the steps to reproduce.

## Rules for content

1. **No diagnoses and no labels.** The tools describe situations and what happens between two people, never a person's psyche. Don't add texts that call anyone a narcissist, an abuser, "avoidant" and so on.
2. **Safety texts stay.** Every tool keeps its "not a diagnosis or therapy" note and its crisis block. Don't remove or soften them.
3. **Examples are invented.** Never paste real messages, real names or anyone's private story, including your own client's.
4. **Plain language.** Short sentences, no jargon without an explanation.
5. **Honest about AI.** Texts written with AI assistance say so. Don't add claims about reviews or validation that did not happen.

## Pull requests

- One topic per pull request.
- If the repo has a build script (`node scripts/build.mjs` or `python3 build.py`), run it and commit the generated files.
- Open the HTML page locally and check both languages before you submit.

## Licence

By contributing you agree that your code is released under MIT and your texts under CC BY 4.0, as in each repo.
