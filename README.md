Veus Edit — The Friendly Beginner’s Guide
For anyone who has never edited a video before. No experience needed — not even with computers. We go one tiny step at a time, and we never use a big word without explaining it.
Hello, and welcome!
You are about to turn the videos, photos and songs on your phone or camera into your very own movie — with titles, effects and music — using a program called Veus Edit. It has a black-and-gold look, it runs on a Windows computer, and it plays your changes live while you work, so you always see what you are making.
Think of editing like cooking:
• Your files (videos, photos, songs) are the ingredients.
• The timeline is your chopping board. You lay things out in the order you want.
• Effects and text are the spices.
• Export is serving the finished dish: a normal video file you can send to friends, upload, or keep.
Nobody gets it perfect the first time, and that is fine. Almost everything can be undone with Ctrl + Z, so be brave and click things.
What you need
• A Windows computer (Windows 10 or 11). A simple laptop is fine. Veus Edit looks at your computer when it starts and adjusts itself, so even an older machine can cope.
• An internet connection, but only for the one-time setup in Part 1 (about 10–20 minutes, mostly waiting).
• A few videos, photos or songs to play with. Phone clips are perfect.
• The file Veus-Edit-source.zip that came with this guide. (If a friend already made the app for you and gave you a file called Veus Edit.exe, skip straight to Part 2.)
Four words you will see all the time
• Click: press the left button of the mouse once. Double-click: press it twice, quickly. Right-click: press the right button; a little menu of choices pops up.
• Drag: press and hold the left button, move the mouse, then let go. Like sliding a card across a table.
• Ctrl + Z (or any shortcut with a plus): hold down the first key, tap the second, then let both go.
• Folder: a box on your computer that holds files. File Explorer (the yellow folder icon at the bottom of your screen) is how you look inside folders.
Part 1 — Getting the app ready (you only do this once)
Here is the idea in plain words: the zip file contains the recipe for Veus Edit. We need to “bake” it once to get the real program. A helper program called Python does the baking for us. You will never have to open Python yourself.
Step 1. Install Python (the helper)
1. Open your web browser (Edge, Chrome, Firefox — any of them) and go to python.org/downloads
2. Click the big yellow button that says Download Python. A file will download, usually into your Downloads folder.
3. Open that file by double-clicking it.
4. Important: at the bottom of the first window, tick the little box Add python.exe to PATH. This one tick prevents most problems later.
5. Click Install Now. If Windows asks “Do you want to allow this app to make changes?” click Yes.
6. Wait until it says Setup was successful, then click Close.
Tip: Download Python from python.org, not from the Microsoft Store. The python.org version works best here.
Step 2. Unpack the zip
A zip file is like a suitcase with the files folded inside. We need to unpack it.
1. Open File Explorer and find Veus-Edit-source.zip (probably in Downloads).
2. Right-click it, choose Extract All…, then click Extract.
3. A normal folder called veusedit opens. Inside you should see files such as build.bat, README.txt and engine.py. If you only see another folder, double-click it until you see build.bat.
4. Move the whole veusedit folder somewhere easy, like your Documents or Desktop.
Please don’t try to run things from inside the zip window. Always unpack first.
Step 3. Build the app
1. In the veusedit folder, find the file named build.bat.
2. Double-click it. A black window with white writing appears. That is normal — it is the computer working, not a virus and not an error.
3. Wait. Lots of text will scroll by. It may take 5 to 15 minutes, depending on your internet. Do not close the window. Go and make tea.
4. When you see SUCCESS and the words Press any key to continue, press any key. The window closes.
5. Open the new folder called dist inside veusedit. Your app is there: Veus Edit (the file ends in .exe).
If the black window says something went wrong, jump to Part 6: When something goes wrong. It is almost always a missing internet connection or the PATH tick from Step 1.
Step 4. Put a shortcut on your Desktop
The easy way: right-click Veus Edit in the dist folder, choose Copy, then right-click an empty spot on your Desktop and choose Paste. Now Veus Edit lives on your Desktop. (The app is one single file, so this is safe.)
Step 5. Open it for the first time
1. Double-click Veus Edit.
2. Windows might show a blue box that says Windows protected your PC. That happens because you made the app on your own computer and it does not come from a big company store. Click More info, then Run anyway.
3. Very rarely, an antivirus program also grumbles about a self-made app. You made it yourself, so if it asks, choose to allow it.
4. You will see a short gold start-up animation, and then the editor opens. Welcome in!
Part 2 — Meet your editing desk (a two-minute tour)
The screen has four main areas. Take a moment to find each one.
• Left side — your shelves. Two tabs: Media (your own files) and Effects (ready-made looks, like Vintage or Glitch).
• Top middle — the Viewer. This is your little TV. You watch your movie here. Under it you will find the gold Play button and the time.
• Bottom middle — the Timeline. This is your chopping board, and it is the most important part. Your movie is laid out here from left (start) to right (end).
• Right side — the Inspector. A row of tabs (CLIP, LOOK, AUDIO, MIXER, TEXT, FX, LAYER, MUSIC, EXPORT, SRT). Click something on the timeline and its settings appear here.
How the timeline is stacked
Imagine sheets of glass lying on top of each other. Whatever is higher on the screen is in front. From top to bottom the lanes are:
1. TEXT — titles and words.
2. FX — effects that happen during a time you choose.
3. LAYER — extra videos, photos, GIFs and stickers that sit on top of the main video (like a small picture in the corner).
4. VIDEO — your main clips, one after another.
5. AUDIO — music, voices and sound effects.
Each lane can hold as many tracks as you like. They are labelled T1, T2 (text), FX1, FX2 (effects), L1, L2 (layers), A1, A2 (audio). If two things happen at the same moment, Veus Edit puts them on different tracks automatically so they never hide each other.
The playhead
The white vertical line with a gold tip is the playhead. It means “this exact moment of your movie”. Click on the row of numbers along the top of the timeline to move it.
The rest of the screen
• Top bar: menus (File, Edit, Effects, Templates, Tools, View, Help) and handy buttons: Import, Undo, Redo, Marker, Preview and the gold Export.
• Bottom strip: a little message line. Veus Edit uses it to give you hints and tell you what it just did. Glance at it often.
Part 3 — Your first movie in 10 steps
Before you start, put two or three short videos, one photo and one song in a folder you can find, such as your Desktop.
Step 1. Bring your files in
Click Import (top left) or press Ctrl + I. Choose your files. To choose several at once, hold the Ctrl key while clicking each one, then click Open. They appear in the Media list on the left.
Veus Edit understands almost every kind of video, photo and music file (MP4, MOV, MKV, AVI, WebM, MP3, WAV, FLAC and many more). If it can’t read one, it tells you why in a message box.
Step 2. Put a clip on the timeline
Double-click a video in the Media list. It lands in the VIDEO lane. Double-click another and it joins on after the first. You can also drag a file from the list and drop it onto the timeline.
Step 3. Press Play
Press the Space bar. Your movie starts playing almost instantly. Press Space again to pause (or click on the Viewer). You can keep editing while it plays, and the picture updates by itself.
Step 4. Jump around
• Click on the number ruler at the top of the timeline to jump there.
• The ← and → arrow keys move one tiny frame at a time. Hold Shift with them to jump one second.
• Or type a time such as 0:12.5 into the little time box next to Play and press Enter.
Step 5. Cut out the boring parts
This is the heart of editing, and it is easy.
• Cut a clip in two: move the playhead to where you want the cut and press S (or click the Split button). Now it is two clips.
• Delete a piece: click the piece you don’t want (it gets a white outline) and press Delete.
• Remove a middle section in one go: move the playhead to the start of the unwanted part and press I. Move to the end of it and press O. Then click Cut. The gap closes by itself.
• Trim by dragging: grab the left or right end of a clip and drag it shorter or longer.
• Made a mistake? Press Ctrl + Z. As many times as you like.
Step 6. Change the order
Drag a clip left or right past its neighbour. They swap places. Easy.
Step 7. Add a title
1. Double-click an empty spot in the TEXT lane (the top lane) at the moment you want the words to appear.
2. The TEXT tab opens on the right. Type your words in the box.
3. Pick a Style from the list. Try Gold on black bar for a cinema look.
4. Drag the text around on the Viewer to place it. Drag the small gold square at its corner to make it bigger or smaller.
5. To make the title last longer, drag its right edge on the timeline.
There is also a visible background box option, outline, shadow, and gentle animations like fade and pop.
Step 8. Add an effect
1. On the left, click the Effects tab.
2. Drag a look (for example Vintage or Glitch) down onto the timeline.
3. The effect starts exactly where you drop it and lasts about 3 seconds. Drag its edges to make it shorter or longer.
4. Want an effect on the whole clip instead? Click the clip, then press Apply to whole clip.
You can stack as many effects as you like; they pile up in rows called FX1, FX2 and so on.
Step 9. Add music
1. Import a song (Step 1).
2. Drag it from the Media list down to the AUDIO lane at the bottom.
3. You will see a wavy picture of the sound. Drag the bar to move it. Drag its ends to trim it.
4. Too loud or too quiet? Open the MIXER tab. Every sound — including the sound that came with your video — has its own slider, plus Mute and Solo buttons.
Step 10. Save, then export
Save your work: press Ctrl + S, give it a name, click Save. This makes a project file (it ends in .veus). It is not a video yet — it is your workspace, so you can come back tomorrow and carry on.
Make the real video: click the gold Export button at the top right. Choose where to save it, give it a name, and click Save. A progress bar shows how it is going. When it finishes, Veus Edit asks if you want to open it. Say yes and watch your very first movie!
Before exporting, glance at the EXPORT tab on the right:
• Format: YouTube 1080p, vertical for TikTok / Reels / Shorts, square for Instagram, and more.
• Quality: Balanced is a great choice for most people.
Want a quick look without the full wait? Click Preview at the top. It makes a fast rough version and opens it in your normal video player.
You did it. That is a real edit. Everything from here is just more spices.
Part 4 — Fun things to try (about a minute each)
• Slow motion or fast forward: click a clip, open the CLIP tab, change Speed. 0.5 is half speed, 2 is double speed.
• Stretch a clip to fit: hold Shift while you drag a clip’s edge. The clip gets slower or faster so it lasts exactly as long as you dragged.
• Play it backwards: CLIP tab, tick Reverse.
• Freeze a frame: move the playhead, then Edit → Freeze frame.
• Change the colours: the LOOK tab has sliders for brightness, contrast and colour, plus a Filter list.
• Green screen: LOOK tab, type the green colour to make it see-through.
• Picture in picture: drag a video onto the LAYER lane. It appears as a smaller window you can drag around in the Viewer. Press Fill frame to make it full size.
• Stickers and GIFs: drop a GIF on the LAYER lane. It loops on its own.
• Smooth transitions between clips: CLIP tab, Transition to next.
• Fade in and out: the two Fade sliders in the CLIP tab.
• Black gaps or coloured backgrounds: Media tab, Colour clip / black gap.
• Ready-made styles: open the Templates menu for TikTok vertical, cinematic widescreen, vlog intro, retro tape and more.
• The Tools menu: record your screen, turn typed words into a spoken voice, make a photo slideshow or a collage, edit many photos at once, or add subtitles from a subtitle file.
• Cut to the beat: click a music bar, right-click it and choose Mark beats. Gold markers appear on every beat, and bars snap to them like magnets.
• Lost? Press Ctrl + K. A search box opens. Type what you want to do (like export or split), press Enter, and it does it.
Part 5 — Cheat sheet (keep it beside your screen)
Moving around
• Space — play / pause
• ← → — one frame back / forward
• Shift + ← → — one second back / forward
• Mouse wheel on the timeline — scroll up and down
• Shift + wheel — scroll left and right
• Ctrl + wheel — zoom in and out (on the timeline or the Viewer)
• Z — zoom the timeline to what you selected
Cutting and editing
• S (or Ctrl + B) — split at the playhead
• Delete — remove the selected item
• I and O — mark In and Out points, then Cut removes that part
• R — razor mode: click any bar to cut it right there
• M — drop a marker
• Ctrl + C / Ctrl + V — copy and paste at the playhead
• Ctrl + D — duplicate
• Alt + ← → — nudge a selected bar by one frame (add Shift for one second)
• Drag an edge — trim or lengthen. Shift + drag an edge — stretch
• Double-click an empty lane spot — add something right there
• Right-click a bar — more choices (split, stretch, copy, delete…)
Everyday
• Ctrl + Z / Ctrl + Y — undo / redo
• Ctrl + S — save   •   Ctrl + O — open   •   Ctrl + N — new
• Ctrl + I — import files   •   Ctrl + E — export
• L — loop playback   •   Ctrl + K — find any command
Part 6 — When something goes wrong (don’t panic)
The black window flashed and vanished when I double-clicked build.bat. Open the veusedit folder, click the address bar at the top of File Explorer, type cmd and press Enter. In the black window that opens, type build.bat and press Enter. Now it will stay open so you can read the message.
It says Python is required or not found. Python is missing or the PATH box was not ticked. Run the Python installer again, choose Modify or reinstall, and make sure Add python.exe to PATH is ticked. Then double-click build.bat again.
It says install failed or check your internet. The setup needs the internet to fetch some parts. Connect, then double-click build.bat again. It simply carries on.
Windows says “Windows protected your PC.” Click More info, then Run anyway.
I can’t hear any sound. Sound plays through your normal speakers or headphones. Check your computer’s volume, then check the MIXER tab for a Mute tick or a slider at zero.
Playback looks a bit choppy. Veus Edit lowers the preview size by itself when your computer is struggling, and raises it again when it can. You can help: close other programs and browser tabs, and avoid huge files if you can. Your exported video is still full quality.
A file won’t import. The message tells you why. The usual causes are a damaged file, or a protected one (for example a bought or rented movie with copy protection). Try a different file.
Exporting is slow. That is normal on older computers, and long or big videos take longer. Pick a smaller Format (such as YouTube 720p) in the EXPORT tab. Keep the computer plugged in and let it work. You can press Cancel at any time.
The app closed by surprise. Don’t worry. Veus Edit saves a backup every minute. Next time you open it, it asks “Recover your unsaved project?” Click Yes.
It says some files were moved or deleted. Your project remembers where your videos live. If you rename or move the originals, point the project to them again by importing them. Tip: keep your files in one folder and don’t move them while you are editing.
I deleted something by mistake. Ctrl + Z. It brings it back.
Still stuck? Veus Edit writes a diary of what happened. Open File Explorer, click the address bar, type %USERPROFILE%\VeusEdit and press Enter. The file veusedit.log is there. Show it to whoever helps you.
Part 7 — Tiny dictionary
• Clip: one piece of video, photo or sound.
• Timeline: the long strip where you arrange your clips in time.
• Playhead: the white line that shows “now”.
• Track / lane: a row on the timeline. Lanes are the five kinds (text, effects, layers, video, audio); tracks are the extra rows inside them.
• Trim: make a clip shorter by pulling its end in.
• Split: cut one clip into two.
• Effect / filter: a ready-made look, such as black and white.
• Transition: a smooth change from one clip to the next.
• Export: turn your project into a real video file.
• Project file (.veus): your saved workspace. It is not a video.
• Proxy: a small stand-in copy Veus Edit makes by itself for very big videos, so editing stays smooth. Your export still uses the originals.
Part 8 — Good habits and gentle tips
• Save early, save often with Ctrl + S. Backups help, but saving is better.
• Keep your original files where they are. Veus Edit never changes your originals; it only reads them.
• Start small. A 30-second movie is a perfect first project.
• Use the right Format for where the video will go: vertical for phones and short videos, YouTube for widescreen.
• Slower computer? Close other programs, edit short projects, and use Preview for quick checks.
• Be curious. Hover, click, drag. Everything can be undone.
What Veus Edit does not do (yet)
So nothing surprises you: it has no automatic background removal, no motion tracking, no online storage or stock music library, and no one-click upload to social sites. Export your video and upload it the usual way. Copy-protected movies cannot be edited.
A little send-off
Every video editor you have ever admired once stared at a screen like this and thought, where do I even start? You started: you now know how to import, cut, add words, add a look, add music and share it. The rest is just play. Go make something you are proud of.
Happy editing — from Veus Edit.
