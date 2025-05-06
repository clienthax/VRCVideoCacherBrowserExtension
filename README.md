# VRCVideoCacherBrowserExtension

A simple browser extension that works with [VRCVideoCacher](https://github.com/EllyVR/VRCVideoCacher) to help cache and play YouTube videos in VRChat.

## ⚠️ Caution

By using your account with tools like this, **you run the risk of your YouTube/Google account being temporarily or permanently banned**. Be cautious about the frequency and volume of requests made while authenticated. Only use your main account if absolutely necessary—**a throwaway account is strongly recommended**.

## Setup Instructions

### 1. Set up the backend

Before using this extension, you need to set up the VRCVideoCacher backend:

- Go to [EllyVR/VRCVideoCacher](https://github.com/EllyVR/VRCVideoCacher) and follow the setup instructions there.
- After installing it, open the `config.json` file and make sure the below setting is set to to true:

```json
{
  "ytdlUseCookies": true
}
```

### 2. Install the extension

#### Chrome / Chromium browsers:

- Install the extension from the chrome store [here](https://chromewebstore.google.com/detail/vrcvideocacher-cookies-ex/kfgelknbegappcajiflgfbjbdpbpokge)
- Make sure to load youtube once in the browser after installing while having VRCVideoCacher running, to setup the cookies

## What it does

This extension passes your YouTube cookies to the VRCVideoCacher backend.

It does this **automatically every time you load a YouTube page**, enabling the backend to access videos as if it were you.

If you run into bot errors, refresh youtube in the browser.