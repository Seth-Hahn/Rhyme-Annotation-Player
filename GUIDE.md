# MUSC 120 RAP — Guide for Teachers and Students

**Class link:** [https://seth-hahn.github.io/Rhyme-Annotation-Player/](https://seth-hahn.github.io/Rhyme-Annotation-Player/)

This guide explains how to use the Rhyme Annotation Player (RAP) in class. No advanced tech skills are required.

---

## What’s new in this version

The following features were added to make RAP easier to use in a real classroom:

### Type directly on the grid
Students no longer need to build a spreadsheet first and upload it. They can click any cell on the grid and type — lyrics, literary devices, beat notes, phrase comments, and more. Drum patterns can still be marked by clicking the grid squares.

### Save and restore
Work is saved automatically in the browser. There is also a **Save now** button, and a **Restore** button to bring back the last saved session on the same device.

### Board tabs
A single “room” can hold **multiple board tabs** — like separate worksheets in one notebook. Each student (or group) can add their own tab with the **+** button. Double-click a tab name to rename it (for example, “Maria” or “Group 3”).

### Share / QR code
Teachers can generate a **QR code** or copyable link so students open RAP on their phones or laptops. **Your annotations are built into the link** — when students scan or click it, they see the grid you prepared (song title, bars, any notes you already entered).

### Compare
Teachers can pick **two board tabs** and see where they differ, with highlights on the grid. Useful for comparing how two students annotated the same verse.

### Export options
- **Export CSV** — a spreadsheet for turning in or grading work.
- **Export board** — a full backup file that can be reopened in RAP later.

### Hosted online (GitHub Pages)
RAP runs in a normal web browser at a shared class link. Students do **not** need to download files, run Terminal commands, or join the same Wi‑Fi network in a special way. They just open the link or scan the QR code.

---

## Teacher workflow

### Before class (one-time)
1. Bookmark the class link: [https://seth-hahn.github.io/Rhyme-Annotation-Player/](https://seth-hahn.github.io/Rhyme-Annotation-Player/)
2. Open it in your browser — **not** by double-clicking a file from your Downloads folder.

### Setting up a lesson
1. Open the class link.
2. Choose a starting template from the **Song** menu (blank grid, or a skeleton preset), or upload a CSV if you already have one.
3. Optionally upload an **audio file** and mark **Bar 1** so playback lines up with the grid.
4. Add any starter annotations you want students to see (or leave the grid blank).
5. Click **Share / QR**.
6. Project the QR code, or post the copied link in Canvas, Slack, or on the board.

### During class
- Tell students to scan the QR code or open the link.
- Remind them to click **+** to create their own board tab (so everyone isn’t editing the same tab).
- Walk around while they annotate on the grid.
- Use **Compare** to look at two students’ work side by side on your screen.

### After class / for grading
- Ask students to **Export CSV** and submit that file (see export section below).
- Or collect **Export board** files if you want to reopen their full session in RAP later.

### Important reminder for teachers
**Re-open Share / QR after you change the grid.** The link and QR code are a snapshot of your work at that moment. If you edit the grid and want students to see the updates, click **Share / QR** again and share the new link or QR code.

---

## Student workflow

### Getting started
1. Open the link your teacher shared, or scan the QR code with your phone camera.
2. Wait for the page to load. You should see the annotation grid (and any notes your teacher already added).
3. Click **+** to add **your own board tab**. Name it with your name or group name (double-click the tab).

### Annotating
1. **Click any cell and type** — lyrics, devices, beat syllables, phrase notes, etc.
2. Click drum squares to mark hi-hat, snare, kick, and non-lexical sounds.
3. Click the **+** on a beat or rhyme column to assign rhyme letters (A, B, C…).
4. Upload audio if your teacher asks you to, then use play and **Mark Bar 1** to sync the grid with the track.

### Turning in work
1. When you’re finished, click **Export CSV**.
2. Submit that file wherever your teacher asks (Canvas, email, etc.).

That’s it. You do not need to install anything or create an account.

---

## Working together: sharing and collaboration

### How sharing works

| Method | What it does | Best for |
|--------|----------------|----------|
| **Share / QR** | Opens RAP with the teacher’s starting grid baked into the link | Starting class, giving everyone the same template |
| **Board tabs (+)** | Each person gets their own sheet inside the same “room” | Students working in parallel on the same assignment |
| **Compare** | Highlights differences between two tabs | Teacher reviewing two students’ work |
| **Export CSV** | Spreadsheet of one tab’s grid | Turning in homework |
| **Export board** | Full save file for RAP | Backup or moving work to another computer |
| **Import board** | Reopens a previously exported board file | Recovering work or opening someone’s full session in RAP |

### How students should collaborate in class

**Recommended approach:**
1. Teacher shares one QR code or link at the start of class.
2. Each student (or group) clicks **+** to make their own tab.
3. Everyone works on their own tab at the same time.
4. The teacher uses **Compare** to discuss differences, or asks students to **Export CSV** to turn in work.

**This is not like Google Docs.** Students do **not** see each other’s typing in real time. Each person’s tab lives in their own browser until they export or the teacher compares tabs on one machine.

### Current limitations (please know these upfront)

1. **No live co-editing.** If Student A is typing, Student B will not see it appear on their screen. There is no real-time sync between devices.

2. **Share / QR is a snapshot.** The link encodes the grid as it looked when the teacher clicked **Share / QR**. Updates after that require sharing a fresh link.

3. **Saving is per device.** Auto-save keeps work on that phone or laptop. If a student clears browser data or uses a different device without exporting, they may lose work.

4. **Compare works on one browser session.** The teacher compares tabs that exist in their session (or after importing student board files). It is not a live view of every student’s screen at once.

5. **Audio files are not shared via the link.** The link shares the **grid**, not the music file. Students may need to upload the same audio themselves, or the teacher should provide the track separately.

6. **Very large annotations make long links.** If a grid is extremely full, the share link can get long. Copy link always works; if a QR code looks crowded, use the copied link instead.

---

## Export CSV vs. Export board

### Export CSV
**What you get:** A spreadsheet file (`.csv`) — one row per bar, with columns for Lyric, Device, Beats, Drums, Syllables, Rhyme, Phrase, Address, Knowledge, Voice.

**Use it when:**
- Turning in an assignment
- Grading in Excel or Google Sheets
- Sharing annotations with someone who does not use RAP
- Printing or reading the analysis as a table

**What it does not include:** Multiple tabs, playback settings (BPM, bar-1 offset), or audio. It exports the grid from your **current tab only**.

---

### Export board
**What you get:** A JSON file (`.json`) — a complete save of your RAP session.

**Use it when:**
- Backing up your work
- Moving a project to another computer (**Import board** to open it)
- Saving multiple tabs together
- Letting the teacher reopen your full session inside RAP

**What it is not for:** Submitting homework in a spreadsheet-friendly format. Most graders will prefer **Export CSV**.

---

### Quick chooser

| I want to… | Use |
|------------|-----|
| Turn in homework | **Export CSV** |
| Grade in a spreadsheet | **Export CSV** |
| Back up my full project | **Export board** |
| Open my work on another computer in RAP | **Export board**, then **Import board** |
| Give the class a starting grid | **Share / QR** |
| See how two annotations differ | **Compare** |

---

## Quick troubleshooting

| Problem | Try this |
|---------|----------|
| QR code doesn’t open on a phone | Make sure the teacher shared the link from the **website**, not a file on their computer. Use the class link above. |
| Grid is empty when student opens the link | Teacher should click **Share / QR** again **after** adding annotations, then share the new QR code. |
| Student lost their work | Check **Restore** on the same device/browser. Otherwise, remind students to **Export CSV** or **Export board** before closing. |
| “Compare” is greyed out | You need at least two board tabs. Click **+** to add another. |

---

## Questions?

For technical setup (updating the site), see `README.md` in this folder.

For classroom use, this guide is the place to start.
