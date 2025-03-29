
# YouNow Emoji Repository 🎨

This repository contains all the emoji used by the [YouNow Custom Emoji Chrome Extension](https://chrome.google.com/webstore/detail).

Each emoji is stored and served via GitHub Pages so the extension can fetch and display them in YouNow chat and the emoji picker.

---

## 📁 Folder Structure

```
younow-emoji/
├── global.json                  # Emoji available everywhere
├── global/                      # Image files for global emoji
│   └── emoji-name.png

├── channels/                    # Channel-specific emoji
│   ├── username.json            # Channel emoji list
│   └── username/
│       └── emoji-name.png       # Images used in that channel
```

---

## ✅ Emoji Rules

- Files must be exactly **100x100** pixels
- Formats: `.png`, `.jpg`, or `.apng` (no `.gif`)
- Filename must match the emoji name (e.g., `party.png` → `#party`)
- To keep emojis sharp and fast-loading, use compressed images

---

## 🌍 `global.json` Format

```json
{
  "party": "https://raw.githubusercontent.com/YOUR_USERNAME/younow-emoji/main/global/party.png",
  "smile": "https://raw.githubusercontent.com/YOUR_USERNAME/younow-emoji/main/global/smile.png"
}
```

---

## 📺 `channels/username.json` Format

```json
{
  "username-wow": "https://raw.githubusercontent.com/YOUR_USERNAME/younow-emoji/main/channels/username/username-wow.png"
}
```

> These emojis only show up when viewing `younow.com/username`.

---

## 🤝 Contributing

If you want emoji added for your channel, join [guilded.gg/coikars](https://www.guilded.gg/coikars) and request it from the team.  
We manually verify and upload emoji for quality and security.

---

## 🧼 Maintainers

This repo is maintained by the creator of the YouNow Custom Emoji extension and trusted staff.

---

Thanks for making chat more expressive! 🎉
