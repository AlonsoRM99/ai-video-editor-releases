# AI Video Editor — Windows releases

Windows beta for editing gaming recordings and OBS replay clips. The editor runs on your PC and opens its interface in your browser. ChatGPT, Python and Node are not required to use the installer.

This repository hosts installer releases and signed update metadata. It contains no recordings, project libraries, Google credentials or private signing key.

## Install

Download the installer from the latest published release, run it, and open **AI Video Editor** from your desktop. See the release's **Getting-started.html** for AI and YouTube setup. The local AI model is a separate one-time installation.

You can install it on a second PC by copying the same installer there. Projects are transferred separately; reconnect YouTube on each computer instead of copying encrypted credentials.

## Update

Version 0.3.0 and later checks signed release information automatically. Open **Updates**, download the available version, save changes in all tabs, then choose **Install update and reopen**. The app refuses installation while processing or uploading is active.

Version 0.2.0 needs the 0.3.0 installer once to gain the updater. A private repository or unpublished release is not accessible to the app's anonymous update checks.

## Beta limitations

The installer is not Windows code-signed. Metadata signatures and download hashes are separate checks from Windows publisher certification. A second clean-PC validation is still required. Editing suggestions are dialogue-based; review the video before publishing. Google API project restrictions can limit uploads to private.

Third-party notices accompany each release. Public distribution readiness, dependency/source compliance and signing are tracked separately from local beta functionality.
