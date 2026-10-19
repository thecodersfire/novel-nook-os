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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for long-form writing, document editing, and ebook organization:

1. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
2. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
3. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
6. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **GNOME Weather** — check local weather conditions (org.gnome.Weather)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
