# Awesome Thymer

> A curated list of awesome Thymer plugins, themes, guides, and resources created by the community.

[Thymer](https://thymer.com) is a note-taking and productivity app. This list collects community-created extensions and resources.

> **Fork note:** this fork of [ed-nico/awesome-thymer](https://github.com/ed-nico/awesome-thymer) merges in community repos not yet in the upstream list (as of 2026-07-05), found by sweeping the public repos of every author already listed.

Install and use plugins at your own risk. It may also be wise to play around with some of these in a test/play workspace before bringing them into your main one.

## Contents

- [Plugins](#plugins)
  - [App Plugins](#app-plugins)
    - [Capture & Import](#capture--import)
    - [Search & Navigation](#search--navigation)
    - [Views & Visualizations](#views--visualizations)
    - [Productivity & Automation](#productivity--automation)
    - [Themes & Styling](#themes--styling)
    - [Text & Editor Enhancements](#text--editor-enhancements)
    - [References & Metadata](#references--metadata)
    - [Journal & Media](#journal--media)
    - [Workspace Utilities](#workspace-utilities)
    - [Sidebar & UI](#sidebar--ui)
    - [Dev Examples](#dev-examples)
  - [Collection Plugins](#collection-plugins)
- [Themes](#themes)
  - [Light & Dark](#light--dark)
  - [Dark Only](#dark-only)
  - [Light Only](#light-only)
- [Contributing](#contributing)

---

## Plugins

> [Plugins Manager](https://github.com/ahpatel/thymer-plugins-manager) - Provides an interface to install, manage, update, import and export any of the compatible App Plugins and Collection Plugins from below.

### App Plugins

App plugins extend the entire Thymer application with global features.

#### Capture & Import

- [Clipboard Parser](https://github.com/RobbK17/thymer-clipboard-parser) - Quickly create Thymer pages from clipboard content
- [CSV Importer](https://github.com/phildrysdale1/Thymer-CSV-Importer) - Import a CSV into a pre-existing collection
- [Export to Markdown](https://github.com/gitdaveuk/thymer-export-to-md) - Export the whole workspace to Markdown
- [Importer](https://github.com/phildrysdale1/thymer-importer) - Import notes from other note apps
- [Multi Image Upload](https://github.com/dantesxj/multi-image-upload) - Batch-upload photos into a Snapshots collection
- [Quick Capture](https://github.com/gitdaveuk/thymer-quick-capture-plugin) - Quickly capture notes from anywhere
- [Quick Capture (ahpatel)](https://github.com/ahpatel/thymer-quick-capture) - Modal quick capture to today's Journal or any page, with tag support
- [Save to Thymer](https://github.com/zakblf/save-to-thymer) - Save web pages to Thymer collections with custom templates and property mapping
- [Thymer Clipper](https://github.com/ahpatel/thymer-clipper) - Chrome-extension web clipper with a companion Thymer plugin
- [Thymer Paste](https://github.com/riclib/thymer-paste) - Converts pasted Markdown into native Thymer blocks (companion queue server/CLI: [thymer-inbox](https://github.com/riclib/thymer-inbox))
- [Web Capture](https://github.com/ahpatel/thymer-web-capture) - Chrome extension + Thymer plugin combo for capturing web links, highlights, and pages
- [Zotero Thyme](https://github.com/harpreetchima/thymer-zotero-thyme) - Import Zotero items into a Sources collection by citekey

#### Search & Navigation

- [Enhanced Search](https://github.com/RobbK17/thymer-enhanced-search) - Cross-collection record viewer with Search, Duplicates, and Compare modes
- [Recent Files](https://github.com/phildrysdale1/thymer-recent-files/) - Adds quick access to your most recently modified files via a pop-up modal
- [Related Notes](https://github.com/ed-nico/thymer-related-notes) - Discovers related notes based on content similarity, shared references, and tags
- [Workflow(y) Search](https://github.com/RobbK17/thymer-workflow-search) - Workflowy inspired incremental search plugin

#### Journal & Media

- [Cadence](https://github.com/harpreetchima/thymer-cadence) - Daily Note into a cadence system with optional weekly, monthly, quarterly, and yearly notes
- [Journal Day Shortcuts](https://github.com/akaready/thymer-journal-day-shortcuts) - Keyboard shortcuts for the previous/next day in the journal
- [Journal Image Gallery](https://github.com/dantesxj/journal-image-gallery) - Renders date-matched images from one or more collections
- [Jump Move Send](https://github.com/akaready/thymer-jump-move-send) - Jump to, move to, or send records to any journal day
- [On This Day](https://github.com/ed-nico/thymer-on-this-day) - Shows your journal entries from this day in previous years
- [Readwise Sync & Daily Highlights Footer](https://github.com/dantesxj/ThymerReadwiseSyncwithDailyFooter) - Sync Readwise Highlights
- [Today's Notes](https://github.com/dantesxj/ThymerTodaysNotesFooter) - Footer on journal entries showing records whose date field matches
- [Weather Moon](https://github.com/dantesxj/weather-moon) - Journal weather and moon data
- [YouTube Timestamp](https://github.com/parham-shafti/thymer-youtube-timestamps) - Add timestamped YouTube links

#### Views & Visualizations

- [BetterKanBan](https://github.com/niklashog/Thymer-plugins/tree/main/BetterKanBan) - Kanban boards with dependency tracking
- [Charts](https://github.com/Braffolk/thymer-charts) - Thymer plugin for creating and using charts
- [Daily Focus (tasks)](https://github.com/niklashog/Thymer-plugins/tree/main/DailyFocus) - A workspace-wide task dashboard that aggregates tasks from across your entire workspace
- [Drive Previewer](https://github.com/Bambouri/Thymer-Google-Drive-Previewer) - Inline previews for Google Drive links (audio, video, PDFs, docs, sheets)
- [Excalidraw](https://github.com/dantesxj/ThymerExcalidraw) - Synced Excalidraw sketches for the active note in a side panel, with bidirectional note links
- [Flashcards](https://github.com/talal/thymer-flashcards) - Create and review flashcards using spaced repetition ([FSRS](https://github.com/open-spaced-repetition/ts-fsrs))
- [Graph](https://github.com/Adel0n/thymer-graph) - Visualize notes as a force-directed graph of connections
- [Graph View](https://github.com/ed-nico/thymer-graph-view) - Renders an interactive force-directed graph of all your notes, references, and tags
- [Markdown Preview](https://github.com/RobbK17/thymer-mdviewer) - Live read-only Markdown rendering of the current record in a panel
- [Tables](https://github.com/phildrysdale1/thymer-tables) - Renders editable tables in HTML

#### Text & Editor Enhancements

- [Collection Icons](https://github.com/akaready/thymer-collection-icons) - Replace the inline-link arrow with each collection's or page's icon
- [Copy Code](https://github.com/adrian18hd/thymer-copy-code-plugin) - Copy code blocks and inline code
- [Editor Tweaks](https://github.com/akaready/thymer-editor-tweaks) - Uniform editor line geometry with indent modes and aligned indent guides, plus tuned hover controls
- [FlowyThymer](https://github.com/ahpatel/flowyThymer) - Workflowy-style row bullets, indent guides, and active-thread highlighting; keeps native row controls visible after folding
- [Font Selector](https://github.com/phildrysdale1/thymer-font-selector/) - Separate interface and note fonts
- [Highlight Line](https://github.com/gitdaveuk/Highlight-Line-Thymer) - Highlight lines in different colours
- [Highlighter](https://github.com/RobbK17/thymer-highlighter) - Obsidian-style `==highlight==` markers rendered as soft yellow highlights
- [Indent Rainbow](https://github.com/ahpatel/thymer-indent-rainbow) - Enhanced hierarchy visualisation with rainbow-colored indent guides and workflowy style bulleting
- [Move To](https://github.com/parham-shafti/thymer-move-to) - Move the current line, block, or selection to any page, heading, or line via a search picker at the caret
- [PDF Highlighter](https://github.com/parham-shafti/thymer-pdf-highlighter) - Turn PDF highlights into notes
- [Thypewriter Scroll](https://github.com/gitdaveuk/Thype-writer-mode) - Keeps the active editor line centered on screen (typewriter mode)
- [Time Command](https://github.com/tomsdev/thymer-time-plugin) - Insert the current time in text
- [Word Count](https://github.com/gitdaveuk/Thymer-Word-Count-Plugin) - Displays a word count for the current page

#### References & Metadata

- [Backlinks with Transclusion](https://github.com/gitdaveuk/minimal-backlinks-thymer) - Shows all notes linking to the open record, with context
- [Backreferences](https://github.com/harpreetchima/thymer-backreferences) - Thymer backreferences footer plugin
- [Bidirectional Fields](https://github.com/parham-shafti/thymer-bidirectional-fields) - Keep two page-link fields in sync as inverses
- [Build Title from Properties](https://github.com/akaready/thymer-build-title-from-properties) - Build collection item display titles from selected property values
- [Property Arranger](https://github.com/parham-shafti/thymer-property-arranger) - Reorder multi-value properties
- [Property Auto-Initiator](https://github.com/parham-shafti/thymer-property-auto-initiator) - Auto populates properties on newly created records
- [Reference Counter](https://github.com/harpreetchima/thymer-reference-counter) - Adds inline reference counters next to record references in the editor
- [Reference Extravaganza](https://github.com/parham-shafti/thymer-reference-extravaganza) - Inline line references, reference aliases, in-place transclusion, and reference/embed conversion (renamed from thymer-reference-aliases)
- [Smart Titles](https://github.com/parham-shafti/thymer-smart-titles) - Show key properties in titles

#### Productivity & Automation

- [App Lock](https://github.com/dantesxj/ThymerAppLockPlugin) - PIN-based Thymer app lock plugin with inactivity auto-lock, manual lock controls, and a hardened sign-out flow
- [Habit Tracker](https://github.com/dantesxj/ThymerHabitTracker) - Habit tracker with journal integration
- [Keyboard Shortcuts](https://github.com/ahpatel/thymer-key-bindings) - Visual editor for browsing, searching, and customizing Thymer keyboard shortcuts
- [Notes Management Plugin](https://github.com/RobbK17/thymer-notes-management) - Unified Thymer custom panel for bulk note operations and advanced tag workflows
- [PDF Export](https://github.com/gitdaveuk/thymer-pdf-export-plugin) - Export notes to PDF
- [Pomodoro Timer](https://github.com/gitdaveuk/thymer-pomodoro-timer) - A pomodoro counter for Thymer
- [PromptPlus](https://github.com/dantesxj/Thymer-PromptPlus) - Create a record in any configured collection with customizable title, prefilled, and prompted fields
- [SyncHub](https://github.com/riclib/thymer-synchub) - Sync architecture for external data sources
- [Workspace Statistics](https://github.com/RobbK17/thymer-statistics) - Comprehensive statistics and analytics for your Thymer workspace
- [YNAB](https://github.com/dantesxj/ThymerYNABBusinessPlugin) - YNAB business dashboard and transaction sync

#### Themes & Styling

- [Theme Architect](https://github.com/asbedb/theme-thyme) - Preview real-time edits to CSS in Thymer

#### Workspace Utilities

- [Backup Viewer](https://github.com/RobbK17/thymer-backup-viewer) - Load a plugin-backup .json and inspect its code and config sections
- [Bulk Move Notes](https://github.com/RobbK17/thymer-bulkmove) - Bulk move notes from one collection to another
- [Bulk Subpage Assigner](https://github.com/RobbK17/thymer-subpage-assigner) - Bulk assign subpages
- [Collection Property Fill](https://github.com/niklashog/Thymer-plugins/tree/main/CollectionPropertyFill) - Set a text property value on every note in a collection
- [Find Empty Files](https://github.com/phildrysdale1/thymer-find-empty-files) - Find empty files in collections
- [Mask Data](https://github.com/RobbK17/thymer-maskdata) - Mask sensitive data (emails, phone numbers, etc.) for screenshots and demos
- [Plugins Manager (jkroes fork)](https://github.com/jkroes/thymer-plugins-manager) - Fork of Plugins Manager with GitHub-only automatic backup and point-in-time restore
- [Scroll to Top](https://github.com/parham-shafti/thymer-scroll-to-top) - Jump back to the top
- [Startup Page Loader](https://github.com/RobbK17/thymer-startup-page-loader) - Automatically open a specific page on startup
- [Tag Renamer](https://github.com/RobbK17/thymer-tagrename) - Rename or bulk-remove tags across the workspace, with preview and an advanced review grid
- [XRay Viewer](https://github.com/RobbK17/thymer-xray-viewer) - Inspect a record's full structure or duplicate it (contents and backreferences) into a new record

#### Sidebar & UI

- [Calendar Widget for Sidebar](https://github.com/gitdaveuk/thymer-sidebar-calendar/tree/main) - Calendar for your sidebar
- [Coinflip](https://github.com/niklashog/Thymer-plugins/tree/main/Coinflip) - Flip a coin from the status bar
- [Collection Colors](https://github.com/akaready/thymer-collection-colors) - Color collection icons and labels in the sidebar
- [Dashboard Status Shortcuts](https://github.com/dantesxj/dashboard-status-shortcuts) - Unified dashboard status bar plus sidebar shortcuts to custom Dashboard views
- [Mac Traffic Lights](https://github.com/akaready/thymer-mac-traffic-lights) - Toggle the macOS window traffic-light buttons on or off
- [Pinned Notes](https://github.com/gitdaveuk/pinned-notes-for-Thymer) - Pins notes to sidebar
- [Sidebar Separators](https://github.com/akaready/thymer-sidebar-separators) - Movable theme-colored separators for the collections list
- [Sidebar Tweaks](https://github.com/akaready/thymer-sidebar-tweaks) - Sidebar visibility, behavior, and layout options
- [Sloppy](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/sidebar-widget) - Character in the sidebar whose eyes follow your cursor
- [Status Bar Clock](https://github.com/gitdaveuk/status-bar-clock-thymer) - Clock in the status bar
- [Status Bar Manager](https://github.com/akaready/thymer-status-bar-manager) - Show or hide individual elements of the bottom status bar

#### Dev Examples

- [Broadcast Demo](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/broadcast) - Real-time messaging between users
- [Clock Plugin](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/clock) - Status bar clock demo
- [CSS Plugin](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/css) - Custom CSS injection demo
- [Move Completed Tasks](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/move-completed-tasks) - Adds a command to move completed tasks to the bottom of their sibling lists
- [Navigate to Journal](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/navigate-to-journal) - Status bar button to open journal
- [Robot Cursor](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/robot-cursor) - Fun cursor customization demo
- [Weather Plugin](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/app-plugins/weather) - Weather display in status bar

### Collection Plugins

Collection plugins extend specific note collections with custom views, formulas, and functionality.

- [Auto-fill View Property](https://github.com/ArtwoXYZ/thymer-auto-fill-view-property) - Fills a "view" property with the current view's name when a record is created
- [Filtered Views](https://github.com/RobbK17/thymer-views) - Create, edit, and delete filtered views for a collection (type, query, sort, visible columns)
- [Hardcover Sync](https://github.com/phildrysdale1/thymer-hardcover-sync/) - Syncs your Hardcover list to a collection
- [Media Tracker](https://github.com/afroviking/thymer-media-plugin) - Track books, movies, and TV shows you've read or watched
- [Supertypes](https://github.com/RobbK17/thymer-supertypes) - Adds typed records with coloured badges, per-type field visibility etc.
- [Weekly Journal](https://github.com/ed-nico/thymer-weekly-journal) - View this week's journal pages side by side

#### Dev Examples

- [Custom Property Render](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/custom-prop-render) - Custom rendering and sorting for table properties
- [Filter Dropdown Choices](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/filter-dropdown-choices) - Dynamic dropdown filtering based on other fields
- [Globe View](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/globe-view) - Interactive 3D globe custom view
- [Kanban Card Button](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/kanban-card-button) - Add custom buttons to kanban cards
- [Kanban Dependencies](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/kanban-dependencies) - Task dependencies on kanban boards
- [Kanban WIP Limits](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/kanban-wip) - Work-in-progress limits per column
- [Org Chart](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/org-chart) - Organogram/hierarchy visualization
- [Real-time Property](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/real-time-property) - Live-updating property values
- [Simple List View](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/simple-list-view) - Basic custom view implementation
- [Table Custom Sort](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/table-custom-sort) - Custom sorting logic for tables
- [Table ID Constraint](https://github.com/thymerapp/thymer-plugin-sdk/tree/main/examples/collection-plugins/table-id-constraint) - Unique ID validation for records

---

## Themes

Custom CSS themes and visual customizations.

### Light & Dark

- [Ayu](https://github.com/phildrysdale1/thymer-ayu-theme) - Light & Dark
- [Blueberry](https://github.com/gitdaveuk/Thymer-Blueberry-Theme) - Light & Dark
- [Catppuccin Latte-Frappe-Macchiato](https://github.com/phildrysdale1/Thymer-Catppuccin-Latte-Frappe-Macchiato) - Light & Dark
- [Chocolatey-Brown](https://github.com/gitdaveuk/Thymer-Chocolatey-Brown-Theme/tree/main) - Light & Dark
- [Coffee Flow State](https://github.com/gitdaveuk/Coffee-Flow-State-Thymer) - Light & Dark
- [Dracula](https://github.com/phildrysdale1/thymer-dracula-theme) - Light & Dark
- [Everforest](https://github.com/phildrysdale1/thymer-everforest-theme) - Light & Dark
- [GitHub](https://github.com/phildrysdale1/thymer-github-themes) - Light & Dark
- [Kanagawa](https://gist.github.com/hildxd/55c6370e287e8f4d89adb6e388e3183b) - Light & Dark
- [Midnight Indigo](https://github.com/gitdaveuk/Midnight-Indigo-Thymer-Theme) - Light & Dark
- [Monokai](https://github.com/phildrysdale1/thymer-monokai-theme) - Light & Dark
- [Night Owl](https://github.com/phildrysdale1/thymer-night-owl-theme) - Light & Dark
- [Nord](https://github.com/phildrysdale1/thymer-nord-theme) - Light & Dark
- [Solarized](https://github.com/phildrysdale1/Thymer-Solarized-Theme) - Light & Dark
- [Terroir Themes](https://github.com/gitdaveuk/terroir-themes-thymer) - Light & Dark (a series of high-contrast one-colour themes, six palettes each in light and dark)
- [Thymer Logseq](https://github.com/gitdaveuk/Logseq-theme-for-Thymer) - Light & Dark
- [Tokyo Night](https://github.com/phildrysdale1/thymer-tokyo-night-theme) - Light & Dark

### Dark Only

- [Blue Sea Dragon](https://github.com/gitdaveuk/blue-sea-dragon-thymer) - Dark Only
- [Catppuccin Mocha](https://github.com/niklashog/Thymer-Catppuccin-Mocha) - Dark Only
- [Dark Deep Focus](https://github.com/gitdaveuk/dark-deep-focus-thymer) - Dark Only
- [Dark Matrix](https://github.com/gitdaveuk/Dark-Matrix-Thymer-Theme) - Dark Only (neon green)
- [Dumbo Octopus](https://github.com/gitdaveuk/Dumbo-Octopus-Theme-Thymer) - Dark Only
- [Green](https://github.com/gitdaveuk/Thymer-Green-Theme) - Dark Only
- [Honeybadger](https://github.com/gitdaveuk/honeybadger-thymer-theme) - Dark Only
- [Obsidian Amber](https://github.com/gitdaveuk/obsidian-amber-theme) - Dark Only
- [One Dark](https://github.com/phildrysdale1/thymer-one-dark-theme) - Dark Only
- [Purple Panther](https://github.com/gitdaveuk/purple-panther-thymer) - Dark Only
- [Sarcastic Fringehead](https://github.com/gitdaveuk/sarcastic-fringehead-thymer) - Dark Only
- [Sengi](https://github.com/gitdaveuk/sengi-theme) - Dark Only (Black and Rufous Sengi)
- [Tuber](https://github.com/gitdaveuk/tuber-thymer-theme) - Dark Only
- [Yeti Crab](https://github.com/gitdaveuk/yeti-crab-theme-thymer) - Dark Only

### Light Only

- [Daylight Soot](https://github.com/niklashog/Thymer-Daylight-Soot) - Light Only
- [Thymer 2008](https://github.com/gitdaveuk/thymer-2008-theme) - Light Only (retro)
- [Watermelon](https://github.com/gitdaveuk/Watermelon-Theme-Thymer) - Light Only

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a resource:
1. Fork this repository
2. Add your resource to the appropriate section
3. Submit a pull request

### Formatting

Use this format when adding items:

```markdown
- [Resource Name](url) - Brief description of what it does
```
