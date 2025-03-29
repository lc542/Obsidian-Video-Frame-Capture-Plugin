# Obsidian-Video-Frame-Capture-Plugin

A simple plugin that lets you capture the current frame of an embedded video in your Obsidian note by pressing a hotkey. The frame is saved as a PNG file.

---

## Features

- Capture video frame as PNG
- Supports pause, seek, and static frames
- Hotkey enabled

---

## How to Install (Locally)

> This plugin is not yet in the Community Store. You can still install it manually.


### 1. Download

Clone or download this repo.


### 2. Copy the plugin folder

Inside the repository, locate the plugin folder:

`.obsidian/plugins/video-frame-capture/`

Copy the entire `video-frame-capture` folder into your vault's plugin directory:

`YourVault/.obsidian/plugins/`

### 3. Enable the plugin in Obsidian

1. Open `.obsidian/community-plugins.json` and add `"video-frame-capture"` to the list. For example:

    ```json
    [
      "sample",
      "video-frame-capture"
    ]
    ```

2. Go to **Settings → Community plugins**
3. Search for `Video Frame Capture` and click **Enable**.
4. Press `Alt + T` while previewing a note with an embedded video to capture the current frame.


### Requirements

1. Your note must contain an embedded video using the syntax:
    ```markdown
    ![[your-video.mp4]]
    ```
2. The plugin works only when the video is visible in Preview mode.