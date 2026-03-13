# Directory Opus — Supersede Buttons

Two custom toolbar buttons for [Directory Opus](https://www.gpsoft.com.au/) that archive files into a `SUPERSEDED` subfolder.

## Buttons

### Supersede
Moves selected file(s) into a `SUPERSEDED` subfolder within the current directory, creating the folder if it doesn't exist.

### Edit & Supersede
Copies selected file(s) to `SUPERSEDED` as a backup, then opens the originals in Notepad++ for editing.

## Installation

1. In Directory Opus, right-click any toolbar and choose **Customize**
2. Drag a `.dcf` file from a lister or Explorer window directly onto the toolbar
3. Click **OK** to exit Customize mode

Repeat for each button.

## Notes

- Both buttons operate on **files only** — selected folders are ignored
- The `SUPERSEDED` folder is created silently; if it already exists, nothing happens
- `edit-supersede.dcf` requires Notepad++ installed at `C:\Program Files\Notepad++\notepad++.exe`
