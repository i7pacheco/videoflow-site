---
title: Privacy — Video Flow
---

# Privacy — Video Flow

Video Flow (the Chrome and Safari extension and the macOS/Windows app) collects no data.
Nothing is sent anywhere: there is no account, no analytics, no telemetry, no crash reports and
no network access of its own.

## Extension

- Runs on every page so its panel can replace the controls of any `<video>`. It reads only those
  video elements; it never reads page content, forms, cookies or history.
- Stores one thing, locally in the browser (`storage.local`, never synced): the list of website
  domain names (for example `example.com`) where you turned the extension off. No paths, queries
  or page titles.
- Speed, loop and position are never stored.

## Desktop app

- Reads only the video files you open (drag and drop, File → Open…, or "Open with"), and only
  while they are open. It never lists folders.
- File paths and names are never written to disk or logs. There is no recent-files list.
- Stores one thing, in the app's settings folder: the window's size and position.

## Contact

Questions or support: [ipachben@gmail.com](mailto:ipachben@gmail.com).
