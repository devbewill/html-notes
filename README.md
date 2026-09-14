# html-notes

A minimal static archive of notes, where each note is a standalone web page.

## Structure

```text
.
├── index.html                         # searchable notes index
└── notes/
    └── magicka-sorcerer/
        ├── index.html                 # standalone note
        └── assets/                    # note-specific assets
```

No build step is required. Open `index.html` directly or serve the folder with any static web server.

## Local preview

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
