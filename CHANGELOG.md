## Version 1.4.6

_November 7, 2026_

### New
- **Capture History.** Browse all your past screenshots in one place, grouped by day. Open any of them in the editor, pin it to the screen, copy it, show it in Finder/Explorer, or delete it. Open it from the home page, the tray menu, or the File menu.
- **Search by text in screenshots.** Type a word you remember seeing and Capture History finds the screenshots containing it. Text is read automatically on your computer and never leaves it.
- **Thumbnail cache setting.** Settings › Files shows how much space Capture History thumbnails use, with a button to clear them.

### Improved
- Pinning a screenshot straight from a capture now shows it exactly as captured, with no added background, padding, corners or shadow.
- On macOS, a pinned window's controls now appear as soon as you hover over it, even when it isn't focused. The close button only shows while hovering.

### Fixed
- Fixed a crash that could happen when using "Open in Editor" from a pinned window. It now reliably opens the editor, or adds a new tab if the editor is already open.
- On macOS, pinned windows now keep the screenshot's proportions when you resize them.

## Version 1.4.5

_October 31, 2026_

### New
- **Undo and redo in the editor.** Each tab has its own history, covering annotations and layout changes like padding, background, border, crop and frame. Use Ctrl/⌘+Z to undo, and Ctrl/⌘+Shift+Z (or Ctrl+Y on Windows) to redo. There are also Undo/Redo buttons in the toolbar.
- **Upload to S3.** Send a screenshot from the editor to your own Amazon S3 or S3-compatible bucket (Cloudflare R2, Backblaze B2, DigitalOcean Spaces, Wasabi, MinIO). The link is copied to your clipboard. Set up buckets in **Settings → S3 Upload**. Uploads go straight from your computer to your bucket. Requires a Basic or Pro license.
- **Keyboard shortcuts in pinned windows:**
  - Copy image: Ctrl/⌘+C
  - Copy all text: Ctrl/⌘+Shift+C
  - Open in editor: Ctrl/⌘+E
  - Zoom in / out: Ctrl/⌘+= / −
  - Original size: Ctrl/⌘+0
  - Close: Esc or Ctrl/⌘+W

### Improved
- **Redesigned capture preview.** It now shows as a thumbnail card in the bottom-left corner. Hover over it to Copy, Edit, Pin or Show in Folder, or use the shortcuts Ctrl/⌘+C, Ctrl/⌘+E, Ctrl/⌘+P and Esc.
- The capture preview appears faster after taking a screenshot.
- Zooming in pinned windows is now smooth.
- Settings, Permissions, Licenses and Export now open in their own windows.
- License activation is now in **Settings → License**, which also shows your plan, email and this device.

### Fixed
- The zoom percentage in pinned windows now updates when you zoom with shortcuts or Ctrl/⌘+scroll.
- On Windows, a screenshot file is no longer locked while its capture preview is open.

### Changes
- macOS: capturing all displays no longer asks which display to keep.
- macOS 12 or later is now required.

## Version 1.4.4

_September 19, 2026_

### 🐛 Bug Fixes

- **Rendering** — Fixed janky rendering when editing screenshots
- **Menu bar** _(macOS only)_ — Fixed the menu bar blinking when editing screenshots

## Version 1.4.3

_July 25, 2026_

### 🔍 Misc. Updates

- **OCR on pinned window** — Improved OCR text detection and added a "Copy All Text" button on the pinned screenshot window

### 🐛 Bug Fixes

- **Image export** _(Mac only)_ — Fixed exported images getting stretched on MacBook displays
- **Pinned window zoom** _(macOS only)_ — Fixed zoom controls causing the pinned window to expand to full height or width
- **Magnifier annotation** — Fixed the connector line disconnecting from rounded corners, and fixed the gap between the magnifier and its radius

## Version 1.4.2

_June 28, 2026_

### 📱 New Device Frames

Added device mockup frames for **iPhone 17**, **iPhone 17 Pro**, **iPhone 17 Pro Max**, and **iPhone Air**.

### 🔍 OCR Text Selection

The editor now supports OCR text selection — select and copy text directly from within your screenshots.

### ✨ New Features

- **Permission check** _(Mac only)_ — Added a Check Permission feature to help verify required system permissions are granted
- **Style profile controls** — New settings to control auto-apply of the default style profile and style panel visibility on open

### 🐛 Bug Fixes

- **Scrolling capture** — Fixed duplicate segments and slow stitching during scrolling capture

---

## Version 1.4.1

_June 21, 2026_

### ✨ New Features

- **Spotlight annotation** — Draw attention to specific areas by dimming everything else around them
- **Layer ordering** — New "Bring to Front" and "Send to Back" options in the annotation context menu
- **Delayed region capture** — Capture a region with a delay, giving you time to set up the shot

### 🔧 Misc. Updates

- Added Documentation, Releases changelog, and Purchase Savvyshot links to the toolbar/menu bar

### 🐛 Bug Fixes

- **Main window** — Fixed the main window not showing up after finishing a screen capture
- **Line annotation** — Fixed line annotations always starting with black instead of the selected color
- **Memory leak** — Fixed a memory leak issue

---

## Version 1.4.0

_June 14, 2026_

### 🎬 Video Backgrounds _(Basic/Pro License Required)_

Bring your screenshots to life with video backgrounds — set a looping video as your screenshot backdrop for eye-catching visuals.

### 🔍 Magnifier Annotation

Zoom in on the details that matter. The new magnifier annotation lets you highlight and enlarge any part of your screenshot inline.

### ✏️ Annotation Improvements

- **Text box** — Revised text box annotation with improved editing experience
- **Shape styles** — Rectangle, circle, and arrow annotations now support **solid**, **semi-transparent**, and **outline only** style options

### ⚡ Capture & Export

- **Preview window** — New option to show a quick preview window instead of jumping straight into the editor after a capture
- **Native share** — Share your screenshots directly via the system's native share popup
- **WebP export** — Export screenshots in WebP format for smaller file sizes

### 🐛 Bug Fixes

- **Screenshot loading** — Fixed slow loading when opening a grabbed screenshot
- **Canvas sizing** — Fixed source image being scaled down when changing the size ratio, and fixed Zoom to Fit behavior
