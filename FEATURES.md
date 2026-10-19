# Built-in features for circuitbench-os

Purpose: electronics schematics, PCB design, and microcontroller projects

1. **prepare a creative project** — run circuitbench-os-workspace. It creates ~/Documents/circuitbench-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run circuitbench-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/circuitbench-os-session-plans/.
3. **check project and export readiness** — run circuitbench-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/circuitbench-os-workspace features/circuitbench-os-plan features/circuitbench-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for electronics schematics, PCB design, and microcontroller projects:

1. **GNOME Builder** — org.gnome.Builder
2. **Wireshark** — org.wireshark.Wireshark
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for electronics schematics, PCB design, and microcontroller projects:

1. **FreeCAD** — design mechanical parts (org.freecadweb.FreeCAD)
2. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
3. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
4. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
