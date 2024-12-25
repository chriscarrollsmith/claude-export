Exploring the Claude data export.

# Usage

1. [Export][ex] your Claude data.
1. You will get an email with a link to download a .zip file (might have a different extension).
1. Put the `conversations.json` file from the export in the `inputs/` folder.
1. Install [Quatro].
1. Install [uv].
1. `uv venv`
1. `source .venv/bin/activate`
1. `uv sync`
1. `quarto preview notebook.qmd`

[ex]: https://support.anthropic.com/en/articles/9450526-how-can-i-export-my-claude-ai-data
[Quatro]: https://quarto.org/
[uv]: https://docs.astral.sh/uv/
