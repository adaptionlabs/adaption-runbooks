# Adding a runbook

1. Copy `templates/runbook.ipynb` into the folder for its product area, e.g. `adaptive-data/combine-datasets.ipynb`.
2. Fill in the header: title, Colab badge path, and docs link.
3. Run it from start to finish against the live API.
4. Clear outputs (_Edit → Clear all outputs_) before committing.
5. Add a row to the table in `README.md`.

## Conventions

- **Standalone.** Each notebook must run on its own in Colab. Install with `%pip install adaption` in the first code cell.
- **No hard-coded keys.** Use the setup cell from the template.
- **Fail loudly.** When polling, check for a `failed` status and raise with the API's error message.
- **Link the blog.** If the feature has a blog post, name the runbook to match it and link the post at the top of the notebook.
- **Reuse blog language.** Introduce sections with wording from the related blog so the runbook cross-references it and surfaces in search.
- **Minimal, API-first cells.** Keep code blocks small and focused on showing the API in action.
