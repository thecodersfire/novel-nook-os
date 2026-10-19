# Built-in features for novel-nook-os

Purpose: long-form writing, document editing, and ebook organization

1. **prepare a creative project** — run novel-nook-os-workspace. It creates ~/Documents/novel-nook-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run novel-nook-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/novel-nook-os-session-plans/.
3. **check project and export readiness** — run novel-nook-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/novel-nook-os-workspace features/novel-nook-os-plan features/novel-nook-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for long-form writing, document editing, and ebook organization:

1. **Zotero** — org.zotero.Zotero
2. **GNOME Calendar** — org.gnome.Calendar
3. **GIMP** — org.gimp.GIMP

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
