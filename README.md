# District 8 Archives

[![Deploy Docs](https://github.com/mn-area35-d08/archives/actions/workflows/deploy-docs.yml/badge.svg?branch=main)](https://mn-area35-d08.github.io/archives/)

## Options

- View the [Archives website](https://mn-area35-d08.github.io/archives/)
- Edit the [Archives **Action Booklet**](https://github.com/mn-area35-d08/archives/tree/main/docs/action-booklet)

## Edit Access

Officers have edit access.
If you would like to help, please contact our DCM.

## Editing

You'll need a free [GitHub account](https://github.com/).

Everything can be edited in a browser.

Action-booklet pages are in the
[docs/action-booklet](https://github.com/mn-area35-d08/archives/tree/main/docs/action-booklet)
folder.

The Markdown files in `docs/` are the editable source of truth.
Our public archive website is generated from those files.

## Privacy and Anonymity Reminder

This is a public archive.
Please follow privacy expectations and the anonymity principles of Traditions 11 and 12.

Do not add private contact information, confidential member details,
full names where anonymity applies, or unpublished financial/account information.

## Optional: Prepare Site on a Local Machine

<details>
<summary>Show command reference</summary>

### In a machine terminal (open in your `Repos` folder)

These are listed for convenience.
For best results,
follow the detailed instructions to set up your local machine in
[pro-analytics-02 guide](https://denisecase.github.io/pro-analytics-02/).

Open a machine terminal in your `Repos` folder:

```shell
git clone https://github.com/mn-area35-d08/archives

cd archives
code .
```

### In a VS Code terminal

These are listed for convenience.
For best results, follow the detailed instructions in
[pro-analytics-02 guide](https://denisecase.github.io/pro-analytics-02/).

```shell
uv self update
uv python pin 3.14
uv lock --upgrade
uv sync --extra docs --upgrade

uv run python -m zensical build

# save progress
git add -A
git commit -m "update"
git push -u origin main
```

## Notes

- Use the **UP ARROW** and **DOWN ARROW** in the terminal to scroll through past commands.
- Use `CTRL+f` to find (and replace) text within a file.

</details>

## Copyright and Use

Materials in this repository are maintained for
District 8 Area 35 archive and service use.

Public access does not grant permission for reuse.
See [LICENSE](LICENSE).
