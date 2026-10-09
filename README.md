# Idea Explorer — team downloads

This is where we share early IdeaSpaces desktop builds. The latest download is **IdeaSpaces Handover v5 for Apple-silicon Macs**. It is an early team build for testing Thread exchanges with colleagues and the updater pipeline. The app source is not in this repository.

[Download the latest hand-over build (v5)](https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest) (choose the `.zip` under **Assets**).

## Install on a Mac

1. Download the zip and double-click it to unpack **IdeaSpaces Handover v5.app**.
2. Move the app to **Applications**.
3. On the first open, right-click the app in Applications and choose **Open**, then approve the macOS prompt if it appears. This team build is **updater-signed with the Tauri minisign key**, but **not Apple Developer ID signed or notarized**; macOS may warn about it on first launch. If macOS does not offer Open, ask us in the Thread rather than turning off your Mac's security settings.
4. In **Start with IdeaSpaces**, choose **Sign in** and use your **ideaspaces.xyz** account in the browser, then return to the app. If you're already signed in on this Mac, you'll see the account menu instead.

You don't need to open a folder to read a Thread. **Your Threads** and **Direct** appear above Create/Open a folder. Open **Direct** first. When a Thread addressed to your exact @handle appears as **new**, open it, read the post and people line, and reply in the field at the bottom. Click **Send reply** once; Enter makes a paragraph and Cmd+Enter sends. A Map attached to a Thread does not grant access to its files.

Questions or trouble installing? **Reply in the Thread where you received the link** so we can work through it together. Don't post account details or passwords in a Thread.

## Updater Manifest

The latest signed updater manifest is published at:
`https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest/download/latest.json`
Verified with Minisign against the public key declared in the app configuration.
EOF
