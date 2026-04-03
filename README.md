# YTNCV (YouTube No Cookie Viewer)

A minimal, cookie-free YouTube player for watching videos and playlists without distractions, ads, or tracking. Designed to work on desktop and mobile devices with a clean, responsive interface.

**[Live Website](https://eman225511.github.io/YTNCV/)**

---

## Features

- Play **individual YouTube videos**, Shorts, and playlists.
- **Cookie-free** player using `youtube-nocookie.com`.
- Responsive **embed container** with a fixed aspect ratio for desktop and mobile.
- **Home button** for easy navigation.
- Clean interface with help text always visible.
- Supports full-screen and picture-in-picture modes.
- Works with:
  - `youtube.com/watch?v=...`
  - `youtu.be/...`
  - Playlists (`?list=...`)

---

## iOS Shortcuts

You can easily open YouTube videos or playlists from your iPhone or iPad using YTNCV Share Sheet Shortcuts. There are three options:

### 1. **YTNCV Watcher (Multi)**
[Get the Shortcut](https://www.icloud.com/shortcuts/e70703fb204d47dca238d894270cfaed)  

- Prompts you to choose **Safari, Chrome, or Web View** when opening a video.
- Ideal if you want **more control** over which browser or web container to use.

### 2. **YTNCV Watcher (BasicS)**
[Get the Shortcut](https://www.icloud.com/shortcuts/3b9c8d8019404a219325d5014fc38841)

- Opens the link directly in **Safari** without asking.
- Ideal for **quick access** and minimal interaction.

### 3. **YTNCV Watcher (BasicC)**
[Get the Shortcut](https://www.icloud.com/shortcuts/b8901e1f4e31430e8c3283f2c14ec795)

- Opens the link directly in **Chrome** without asking.
- Ideal for **quick access** and minimal interaction.

**How to use either shortcut:**

1. Install the shortcut from the links above.
2. Open **YouTube** (or any app that can share URLs) and tap the **Share** button on a video or playlist.
3. Select the **YTNCV shortcut** from the share sheet.
4. The video or playlist will open directly in YTNCV for playback in a clean, cookie-free environment.

---

## Usage on the Website

1. Open the [YTNCV page](https://eman225511.github.io/YTNCV/) in your browser.
2. Paste a YouTube link (video, Shorts, or playlist) in the input field.
3. Click the **▶** button or press **Enter**.
4. The video or playlist will appear in the embed container above the help text.
5. You can also load a video directly via the URL:  
   `https://eman225511.github.io/YTNCV/?yt={YTLINK}`

---

## Layout & Controls

- **Top bar**:  
  - Home button (SVG icon) on the left.  
  - Input field in the middle for pasting links.  
  - Play button on the right.
- **Embed container**:  
  - Dynamically adjusts for mobile and desktop using a 16:9 ratio.  
  - Maximum height for large screens to prevent overflow.  
- **Info panel**:  
  - Displays instructions, supported links, and usage tips.
 
---

## Example URLs

Single video:  
https://www.youtube.com/watch?v=dQw4w9WgXcQ  

Shortened URL:  
https://youtu.be/dQw4w9WgXcQ  

Playlist:  
https://www.youtube.com/playlist?list=PL9tY0BWXOZFvZ1NQHq0kV5fJ7yXw4w3M2
