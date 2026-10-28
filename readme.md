# Veus Edit — The Friendly Beginner’s Guide

> **For anyone who has never edited a video before.** No experience needed — not even with computers. We go one tiny step at a time, and we never use a big word without explaining it.

---

## Welcome!

You are about to turn the videos, photos, and songs on your phone or camera into your very own movie — with titles, effects, and music — using a program called **Veus Edit**. It has a black-and-gold look, runs on a Windows computer, and plays your changes live while you work, so you always see what you are making.

### Think of editing like cooking:
* 🥦 **Your files** (videos, photos, songs) are the ingredients.
* 🔪 **The timeline** is your chopping board. You lay things out in the order you want.
* 🧂 **Effects and text** are the spices.
* 🍽️ **Export** is serving the finished dish: a normal video file you can send to friends, upload, or keep.

*Nobody gets it perfect the first time, and that is fine. Almost everything can be undone with **`Ctrl + Z`**, so be brave and click things!*

---

## What You Need

* **A Windows computer** (Windows 10 or 11). A simple laptop is fine. Veus Edit looks at your computer when it starts and adjusts itself, so even an older machine can cope.
* **An internet connection**, but only for the one-time setup in Part 1 (about 10–20 minutes, mostly waiting).
* **A few videos, photos, or songs** to play with. Phone clips are perfect.
* **The file `Veus-Edit-source.zip`** that came with this guide. *(If a friend already made the app for you and gave you a file called `Veus Edit.exe`, skip straight to Part 2.)*

---

## Four Words You Will See All the Time

1. **Click**: Press the left button of the mouse once. 
   * **Double-click**: Press it twice, quickly. 
   * **Right-click**: Press the right button; a little menu of choices pops up.
2. **Drag**: Press and hold the left button, move the mouse, then let go. Like sliding a card across a table.
3. **`Ctrl + Z` (or any shortcut with a plus)**: Hold down the first key, tap the second, then let both go.
4. **Folder**: A box on your computer that holds files. **File Explorer** (the yellow folder icon at the bottom of your screen) is how you look inside folders.

---

## Part 1 — Getting the App Ready (You Only Do This Once)

> **The Idea:** The zip file contains the recipe for Veus Edit. We need to “bake” it once to get the real program. A helper program called **Python** does the baking for us. You will never have to open Python yourself.

### Step 1. Install Python (the helper)
1. Open your web browser (Edge, Chrome, Firefox) and go to [python.org/downloads](https://www.python.org/downloads/).
2. Click the big yellow button that says **Download Python**. A file will download, usually into your Downloads folder.
3. Open that file by double-clicking it.
4. **IMPORTANT:** At the bottom of the first window, tick the little box **Add python.exe to PATH**. *This one tick prevents most problems later.*
5. Click **Install Now**. If Windows asks *"Do you want to allow this app to make changes?"* click **Yes**.
6. Wait until it says **Setup was successful**, then click **Close**.

> 💡 **Tip:** Download Python from python.org, not from the Microsoft Store. The python.org version works best here.

### Step 2. Unpack the zip
1. Open **File Explorer** and find `Veus-Edit-source.zip` (probably in Downloads).
2. Right-click it, choose **Extract All…**, then click **Extract**.
3. A normal folder called `veusedit` opens. Inside you should see files such as `build.bat`, `README.txt`, and `engine.py`. *(If you only see another folder, double-click it until you see `build.bat`.)*
4. Move the whole `veusedit` folder somewhere easy, like your Documents or Desktop.

*Please don’t try to run things from inside the zip window. Always unpack first.*

### Step 3. Build the app
1. In the `veusedit` folder, find the file named `build.bat`.
2. Double-click it. A black window with white writing appears. That is normal — it is the computer working, not a virus and not an error.
3. **Wait.** Lots of text will scroll by. It may take 5 to 15 minutes, depending on your internet. Do not close the window. Go and make tea.
4. When you see **SUCCESS** and the words `Press any key to continue`, press any key. The window closes.
5. Open the new folder called `dist` inside `veusedit`. Your app is there: **Veus Edit** (the file ends in `.exe`).

*(If the black window says something went wrong, jump to Part 6: When something goes wrong.)*

### Step 4. Put a shortcut on your Desktop
Right-click `Veus Edit` in the `dist` folder, choose **Copy**, then right-click an empty spot on your Desktop and choose **Paste**. Now Veus Edit lives on your Desktop.

### Step 5. Open it for the first time
1. Double-click **Veus Edit**.
2. Windows might show a blue box that says *Windows protected your PC*. That happens because you made the app on your own computer and it does not come from a big company store. Click **More info**, then **Run anyway**.
3. Very rarely, an antivirus program also grumbles. You made it yourself, so if it asks, choose to allow it.
4. You will see a short gold start-up animation, and then the editor opens. Welcome in!

---

## Part 2 — Meet Your Editing Desk (A 2-Minute Tour)

The screen has four main areas:

* **Left side — your shelves:** Two tabs: **Media** (your own files) and **Effects** (ready-made looks, like Vintage or Glitch).
* **Top middle — the Viewer:** This is your little TV. You watch your movie here. Under it you will find the gold Play button and the time.
* **Bottom middle — the Timeline:** This is your chopping board, and it is the most important part. Your movie is laid out here from left (start) to right (end).
* **Right side — the Inspector:** A row of tabs (`CLIP`, `LOOK`, `AUDIO`, `MIXER`, `TEXT`, `FX`, `LAYER`, `MUSIC`, `EXPORT`, `SRT`). Click something on the timeline and its settings appear here.

### How the Timeline is Stacked
Imagine sheets of glass lying on top of each other. Whatever is higher on the screen is in front. From top to bottom the lanes are:

1. **TEXT** — titles and words.
2. **FX** — effects that happen during a time you choose.
3. **LAYER** — extra videos, photos, GIFs and stickers that sit on top of the main video (like a small picture in the corner).
4. **VIDEO** — your main clips, one after another.
5. **AUDIO** — music, voices and sound effects.

Each lane can hold as many tracks as you like (`T1`, `T2`, `FX1`, `FX2`, `L1`, `L2`, `A1`, `A2`). If two things happen at the same moment, Veus Edit puts them on different tracks automatically so they never hide each other.

### The Playhead
The white vertical line with a gold tip is the **playhead**. It means *"this exact moment of your movie"*. Click on the row of numbers along the top of the timeline to move it.

### The Rest of the Screen
* **Top bar:** Menus (*File*, *Edit*, *Effects*, *Templates*, *Tools*, *View*, *Help*) and handy buttons: *Import*, *Undo*, *Redo*, *Marker*, *Preview*, and the gold *Export*.
* **Bottom strip:** A little message line. Veus Edit uses it to give you hints and tell you what it just did. Glance at it often.

---

## Part 3 — Your First Movie in 10 Steps

*Before you start, put two or three short videos, one photo, and one song in a folder you can find, such as your Desktop.*

1. **Bring your files in:** Click **Import** (top left) or press `Ctrl + I`. Choose your files. (Hold `Ctrl` while clicking to select multiple). They appear in the Media list on the left.
2. **Put a clip on the timeline:** Double-click a video in the Media list. It lands in the `VIDEO` lane. Double-click another and it joins on after the first. You can also drag and drop.
3. **Press Play:** Press the `Space bar`. Press `Space` again to pause. You can keep editing while it plays!
4. **Jump around:** Click the number ruler at the top of the timeline to jump. Use `←` and `→` arrow keys to move frame by frame (`Shift` + arrow jumps one second).
5. **Cut out the boring parts:**
   * *Cut in two:* Move playhead, press `S` (or click *Split*).
   * *Delete:* Click unwanted piece, press `Delete`.
   * *Remove middle section:* Move playhead to start, press `I`. Move to end, press `O`. Click *Cut*.
   * *Trim:* Drag the left or right end of a clip shorter or longer.
6. **Change the order:** Drag a clip left or right past its neighbour to swap places.
7. **Add a title:** Double-click an empty spot in the `TEXT` lane. Type your words in the right tab, pick a style, and drag it into position on the Viewer.
8. **Add an effect:** Click the **Effects** tab on the left. Drag a look (e.g., *Vintage*) down onto the timeline. Drag its edges to adjust duration.
9. **Add music:** Drag a song from Media down to the `AUDIO` lane. Adjust sound levels in the **MIXER** tab.
10. **Save, then export:** 
    * Save project workspace: `Ctrl + S` (saves as `.veus`).
    * Make real video: Click gold **Export** button, select options in `EXPORT` tab, and click Save!

---

## Part 4 — Fun Things to Try (1 Minute Each)

* **Slow motion / Fast forward:** Click clip $\rightarrow$ `CLIP` tab $\rightarrow$ change Speed (`0.5` = half speed, `2` = double speed).
* **Stretch clip to fit:** Hold `Shift` while dragging a clip's edge.
* **Play backwards:** `CLIP` tab $\rightarrow$ tick **Reverse**.
* **Freeze frame:** Move playhead $\rightarrow$ *Edit* $\rightarrow$ *Freeze frame*.
* **Change colours:** `LOOK` tab sliders (brightness, contrast, filters).
* **Green screen:** `LOOK` tab $\rightarrow$ select green color to make transparent.
* **Picture in Picture:** Drag video onto `LAYER` lane.
* **Cut to the beat:** Right-click music bar $\rightarrow$ select **Mark beats**. Bars will snap to beat markers!
* **Lost?** Press `Ctrl + K` to open the quick search box. Type what you want to do.

---

## Part 5 — Shortcut Cheat Sheet

| Category | Shortcut | Action |
| :--- | :--- | :--- |
| **Moving Around** | `Space` | Play / Pause |
| | `←` / `→` | 1 frame back / forward |
| | `Shift` + `←` / `→` | 1 second back / forward |
| | `Ctrl` + `Wheel` | Zoom in / out |
| | `Z` | Zoom to selection |
| **Cutting & Editing**| `S` (or `Ctrl + B`)| Split clip at playhead |
| | `Delete` | Remove selected item |
| | `I` and `O` | Mark In / Out points for cutting |
| | `R` | Razor mode (click to cut) |
| | `M` | Drop a marker |
| | `Ctrl + C` / `Ctrl + V` | Copy / Paste |
| | `Ctrl + D` | Duplicate |
| | `Alt` + `←` / `→` | Nudge bar by 1 frame |
| **Everyday** | `Ctrl + Z` / `Ctrl + Y` | Undo / Redo |
| | `Ctrl + S` | Save project |
| | `Ctrl + I` / `Ctrl + E` | Import files / Export video |
| | `Ctrl + K` | Find any command |

---

## Part 6 — Troubleshooting (Don't Panic!)

* **Black window vanished instantly:** Open `veusedit` folder, click top address bar, type `cmd`, press Enter. In the window, type `build.bat` and press Enter to read the error message.
* **Says "Python required or not found":** Run Python installer again $\rightarrow$ choose **Modify** $\rightarrow$ ensure **Add python.exe to PATH** is ticked.
* **No Sound:** Check computer volume and check the `MIXER` tab in Veus Edit for muted channels.
* **Choppy Playback:** Close background apps/browser tabs. The preview quality automatically adjusts, but your final exported video will be full quality.
* **App closed by surprise:** Veus Edit auto-saves every minute. Re-open the app and click **Yes** when asked to recover your project.
* **Log File:** If stuck, find detailed logs at `%USERPROFILE%\VeusEdit\veusedit.log`.

---

## Part 7 — Tiny Dictionary

* **Clip:** One piece of video, photo, or sound.
* **Timeline:** The long strip where you arrange your clips in time.
* **Playhead:** The white line that shows "now".
* **Track / Lane:** Rows on the timeline.
* **Trim:** Make a clip shorter by pulling its end in.
* **Split:** Cut one clip into two.
* **Export:** Turn your project into a real video file.
* **Project File (`.veus`):** Your saved workspace (not a video file).
* **Proxy:** A temporary small stand-in copy made for big videos to keep editing smooth.

---

## Part 8 — Good Habits & Limitations

### Good Habits
* Save early and often (`Ctrl + S`).
* Keep your original files in one folder and don't move or rename them while editing.
* Start small (a 30-second movie is great for practice).

### What Veus Edit Does Not Do (Yet)
* No automatic background removal.
* No motion tracking.
* No stock music library or online cloud storage.
* No direct one-click upload to social media (export first, then upload).
* Copy-protected movies cannot be edited.

---

*Happy editing — from **Veus Edit**!*