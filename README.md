# IdeaExplorer — team downloads

This is where we share early IdeaSpaces desktop builds. The latest download is **IdeaExplorer for Apple-silicon Macs** (0.8.0). It is an early team build for testing Thread exchanges, private Git operations, and the updater pipeline. The app source is closed and not in this repository.

[Download IdeaExplorer (0.8.0 DMG)](https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest) (choose the `.dmg` under **Assets**).

## Install on a Mac

1. Download the DMG and open it.
2. Drag **IdeaExplorer** to **Applications**.
3. On first launch:
   - Double-click **IdeaExplorer** in **Applications**.
   - macOS will display a prompt indicating the app cannot be opened because Apple cannot check it for malicious software (the app is **updater-signed with Tauri Minisign and ad-hoc bundle signed**, but **not Apple Developer ID signed or notarized**).
   - Open **System Settings** → **Privacy & Security**, scroll down to **Security**, and click **Open Anyway** next to **IdeaExplorer** (or right-click → **Open** on macOS versions before Sequoia).
   - Click **Open** on the confirmation dialog.
4. If you run IdeaExplorer from outside Applications (for example, directly from Downloads), the app will offer to move itself to Applications and relaunch.
5. In **Start with IdeaSpaces**, choose **Sign in** and use your **ideaspaces.xyz** account in the browser, then return to the app. If you're already signed in on this Mac, you'll see the account menu instead.

## Updating from Existing Installs (v9)

If you already have an earlier build installed (such as `IdeaSpaces Handover v8.app` running v9 / 0.7.5):
1. In the app menu, choose **Check for Updates…** and install the update.
2. The update installs in place and retains all your local data and sign-in credentials.
3. After quitting, rename the application folder in Finder (for example, `IdeaSpaces Handover v8.app` or `IdeaSpaces Handover v9.app`) to **`IdeaExplorer.app`**.

## Using Threads

You don't need to open a folder to read a Thread. **Your Threads** and **Direct** appear above Create/Open a folder. Open **Direct** first. When a Thread addressed to your exact @handle appears as **new**, open it, read the post and people line, and reply in the field at the bottom. Click **Send reply** once; Enter makes a paragraph and Cmd+Enter sends. A Map attached to a Thread does not grant access to its files.

Questions or trouble installing? **Reply in the Thread where you received the link** so we can work through it together. Don't post account details or passwords in a Thread.

## Updater Manifest

The latest signed updater manifest is published at:
`https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest/download/latest.json`
Verified with Minisign against the public key declared in the app configuration.
