# Idea Explorer

Idea Explorer is a Mac app for working with AI agents on your own files. You keep notes and projects in folders on your Mac and talk to an agent about them, using the Claude or ChatGPT account you already have. When you want other people in, you share the work on a Thread, and each person brings their own agent.

## Download

**[Download Idea Explorer 0.9.15 for Apple-silicon Macs](https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest)**

Under **Assets**, choose the `.dmg` file. It's named `IdeaSpaces_0.9.15_aarch64.dmg`, and the app inside is Idea Explorer.

## What you need

- An Apple-silicon Mac with macOS 13.5 or later.
- A Claude or ChatGPT account, or Claude Code already signed in.
- No IdeaSpaces account, unless you want to share or join Threads online.

## Install

Open the DMG, drag Idea Explorer to Applications and open it. The app is signed and notarized, so macOS asks once to confirm and there is no Open Anyway step.

## Your first ten minutes

1. Create a Vault. A Vault is just a folder on your Mac, and Home shows you where it is.
2. Connect a model. Sign in with your Claude or ChatGPT account. If you already use Claude Code, run `claude` once in a terminal to sign in.
3. Answer "What is this place for?" in your first conversation.

## Your data

- **Your files** stay in the folders you choose.
- **Conversations** live in the app's data folder, `~/Library/Application Support/xyz.ideaspaces.desktop.handover/`, with any images you attach. If you use Claude Code, it also keeps its own record in `~/.claude`.
- **What you write, and what your agent reads,** goes to the model provider you chose.
- **Threads on IdeaSpaces** are stored on IdeaSpaces and shared with their members. Threads in your Vault stay in your Vault.
- **Sign-ins** stay on this Mac. Your IdeaSpaces sign-in is in the macOS Keychain.
- **Update checks:** the app asks GitHub for a new version each time it opens.
- **Images and videos from the web** in a Note load only when you click them.

### Agents on shared Threads

An agent working on a shared Thread reads what other people wrote and keeps all its tools: it can run commands, read and change the files on your Mac, and reach the internet. A post written to trick it could make it do something you didn't ask for, such as sending your files to someone else, so use an agent only on Threads with people you trust.

## Updates

When a new version is out, the app offers it when it opens, and installs only when you click **Install and restart**. You can also choose **Idea Explorer → Check for Updates…**. Your Vaults, conversations and tabs stay.

## Removing it

1. To remove your IdeaSpaces sign-in from this Mac, sign out in Settings → Account.
2. Quit Idea Explorer and move it from Applications to the Trash.
3. To remove your conversations and settings too, delete these folders:
   - `~/Library/Application Support/xyz.ideaspaces.desktop.handover/`
   - `~/Library/Caches/xyz.ideaspaces.desktop.handover/`
   - `~/Library/WebKit/xyz.ideaspaces.desktop.handover/`

If you used Claude Code, its own record stays in `~/.claude`.

Your Vaults are ordinary folders, so they stay until you delete them.

## Known limits

- A conversation can't be deleted yet, so the images saved with it stay on disk.
- A Thread in your Vault stays local: to work with someone, start a Thread on IdeaSpaces.
- Idea Explorer is tested with Claude Code 2.1.318. The app uses whichever version you have installed, and another version may not behave the same way.
- The full list is in [the latest release](https://github.com/IdeaSpaces-xyz/idea-explorer/releases/latest).

## Coming from v2

v2 doesn't update to this app by itself, so download the DMG above. Idea Explorer installs beside your v2 app and leaves v2's files alone, but it doesn't read them: you start with no Vault, tabs or conversations, and you sign in again. Quit one app before you open the other.

## Help and more

The Explorers' Manual is at [manual.ideaspaces.xyz](https://manual.ideaspaces.xyz).

## License and third-party software

Idea Explorer's source is closed; this repository holds its releases. Each release attaches the source of the Git it bundles, as `git-2.53.0.tar.xz` for this version.

## Older v2 releases

Older builds are further down [the releases page](https://github.com/IdeaSpaces-xyz/idea-explorer/releases), marked as v2. Their tags start with `ideaexplorer-` or `handover-`. They aren't notarized, so macOS asks you to allow them under System Settings → Privacy & Security → Open Anyway.
