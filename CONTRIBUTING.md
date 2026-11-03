# Adding a runbook

1. Copy `templates/runbook.ipynb` into the folder for its product area, e.g. `adaptive-data/combine-datasets.ipynb`.
2. Fill in the header: title, Colab badge path, docs link, runtime, and cost.
3. Run it from start to finish against the live API.
4. Clear outputs (_Edit → Clear all outputs_) before committing.
5. Add a row to the table in `README.md`.

## Conventions

- **Standalone.** Each notebook must run on its own in Colab. Install with `%pip install adaption` in the first code cell.
- **No hard-coded keys.** Use the setup cell from the template.
- **Fail loudly.** When polling, check for a `failed` status and raise with the API's error message.
- **Say what it costs.** State runtime and credit cost in the header.
