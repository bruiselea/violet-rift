# nu pixel icons and square controls

Violet Rift 0.2.0 includes 88 original 16x16 SVG icons, with 255 icon-name mappings.
Open `Icons/index.html` for the gallery. `Icons/icon-map.json` lists every mapping.
The theme embeds the masks locally; no icon plugin or internet request is required.
The raw SVGs are included for finished design use under the public preview license.

Covered standard areas include Files, Search, Quick Switcher, Graph, Canvas, Bases,
Bookmarks, Daily Notes, Templates, Outline, Backlinks, Outgoing Links, Properties,
Command Palette, Workspaces, File Recovery, Note Composer, Audio Recorder,
Random Note, Slides, Publish/Sync-related controls and common editing/navigation UI.
Icons apply when the named SVG is present; some standard features share an icon.
A shared icon cannot uniquely identify the plugin that uses it.
Custom third-party plugin icons may retain their own artwork.

Tabs, button surfaces, settings cards, search fields, menus, tooltips, tags, toggles,
sliders and checkboxes use square corners. Tabs no longer draw curved join fillers.
Radio options keep a separate filled-center state. Accessible labels and click handlers
remain provided by Obsidian; the theme only changes presentation.
The font is still a separate opt-in CSS snippet.

macOS-owned window corners, traffic-light buttons, native context menus and file dialogs
are outside the theme's control. This package does not patch macOS or ship native code.
Other appearance snippets or third-party plugin CSS can override these styles.

## Review status

macOS Obsidian 1.14.4: square tabs, common controls and first-pass pixel icon substitution
were observed in the isolated demo Vault. The settings screen (square toggles, slider,
search and dropdown), native-ID sidebar/help icons, custom context menu, and
reading/editing view switch were also checked in the app after the Mac was unlocked.
Windows, Linux and mobile remain untested. Not every mapped icon was exercised in UI.
