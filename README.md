# ScriptWriter — Stage Play & Theatre Script Editor

A free, browser-based editor for writing stage plays and theatre scripts. No account, no sign-up, no software to install — just open and start writing.

🔗 **[Open ScriptWriter](https://rbeadle21.github.io)**  
📥 **[Download for Offline Use](https://rbeadle21.github.io)** — click the *Download App* button on the site

---

## Features

### ✍️ Script Editor
- Block-based formatting for **Acts, Scenes, Dialogue, Stage Directions, Songs, Intervals, Parentheticals** and more
- Character name auto-complete as you type
- Drag and drop to reorder any block
- Click the block type label to instantly change it (e.g. Stage Direction → Dialogue)
- Choose from **Modern** or **Classic/Shakespeare** layouts
- Font options including **OpenDyslexic** for accessibility
- Auto-saves to your browser as you write

### 🎭 Actor Zone
A dedicated space for cast members to work with their own copy of the script:
- Upload a `.playwriter.json` file shared by the director/writer
- Select your character(s) from the cast list
- **Full Script** view — whole script with your lines highlighted
- **My Scenes** view — only the scenes you appear in
- **Cue Script** view — your cue lines followed by your line only
- **Self-Test Mode** — hides your lines so you can test yourself; click to reveal one at a time
- Stats panel showing your line count, word count, and scenes

### 🎬 Screenplay Mode
- Dedicated screenplay formatting view
- Standard screenplay layout with scene headings, action, and dialogue

### 📋 Cast List
- Manage characters with descriptions in the sidebar
- Cast list appears on the printed script page

### 💾 File Management
- **Save** — saves your project as a `.playwriter.json` file using a native save dialog (choose your own location)
- **Load** — open any previously saved `.playwriter.json` file
- **Import** — import from Word (`.docx`), PDF, or existing ScriptWriter files
- **New** — start a fresh project (with confirmation so you don't lose work)
- **Print / PDF** — print or export to PDF directly from your browser

---

## For Directors & Writers — Sharing with Your Cast

The best workflow for sharing with actors:

1. Write or import your script in the **Script Editor**
2. Check through the blocks — use the **⇄** button on any block to fix its type if needed
3. Check the **Cast List** in the sidebar has all character names correct
4. Click **💾 Save** and save the `.playwriter.json` file
5. Share that file with your cast (email, WhatsApp, Google Drive, Dropbox — anything works)
6. Actors open ScriptWriter, go to the **Actor Zone** tab, upload the file, and select their character

> **Why `.playwriter.json` and not Word or PDF?**  
> The `.playwriter.json` file preserves everything — character names, block types, cast list — exactly as you set them up. Word and PDF files have to be re-parsed each time, which can introduce errors with unusual formatting.

---

## Using Offline

ScriptWriter is designed to work completely offline once downloaded.

**To get the offline version:**
1. Visit [rbeadle21.github.io](https://rbeadle21.github.io)
2. Click the **⬇ Download App** button in the top bar
3. Save the file as `ScriptWriter.html`
4. Open it in any browser — no internet needed

**To update to the latest version**, just visit the site and download again.

---

## Troubleshooting

**Script looks out of date after a site update?**  
Your browser may be showing a cached version. Force a fresh load with a hard refresh:
- **Windows / Linux:** `Ctrl + Shift + R`
- **Mac:** `Cmd + Shift + R`

**Something not working as expected?**  
Try refreshing the page — most minor glitches clear on their own. Save your work first with **💾 Save** if you have unsaved changes. If the issue persists, get in touch.

**Found a bug or have a suggestion?**  
Email: scriptworkstudio@hotmail.com

---

## Technical Notes

- **Single HTML file** — no dependencies, no build process, no server required
- Works fully offline once loaded or downloaded
- All script data is stored locally in your browser — nothing is sent to a server
- Word and PDF imports use [Mammoth.js](https://github.com/mwilliamson/mammoth.js) and [PDF.js](https://mozilla.github.io/pdf.js/) — loaded once from a CDN then cached by the browser
- Two versions are maintained:
  - `index.html` — the online version (includes the Download App button)
  - `ScriptWriter.html` — the offline version (no download button, clean interface)

---

## License

Free to use for educational, theatrical, and personal use.

---

*Built by [Script Work Studio](https://buymeacoffee.com/scriptworkstudio) — free tools for education and the arts.*
