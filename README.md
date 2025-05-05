
# VRCVideoCacherBrowserExtension

A simple browser extension that works with [VRCVideoCacher](https://github.com/EllyVR/VRCVideoCacher) to help cache and play YouTube videos in VRChat.

## Setup Instructions

### 1. Set up the backend

Before using this extension, you need to set up the VRCVideoCacher backend:

- Go to [EllyVR/VRCVideoCacher](https://github.com/EllyVR/VRCVideoCacher) and follow the setup instructions there.
- After installing it, open the `config.json` file and make sure these settings are set:

```json
{
  "ytdlGeneratePoToken": false,
  "ytdlUseCookiesFromBrowserExtension": true
}
```

### 2. Install the extension

#### Chrome / Chromium browsers:

- Download or clone this repository.
- Go to `chrome://extensions/`.
- Enable **Developer mode**.
- Click **Load unpacked** and select the chrome folder.

## What it does

This extension passes your YouTube cookies to the VRCVideoCacher backend.

---