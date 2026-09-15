# Runboo Workflows

Runboo keeps terminal sessions running while you close or reopen its interface.
Download native applications from [Releases](https://github.com/RunbooAI/workflows-releases/releases).

## Install

### Linux and macOS

```sh
curl -fsSL https://github.com/RunbooAI/workflows-releases/releases/latest/download/install.sh | sh
```

### Windows PowerShell

```powershell
irm https://github.com/RunbooAI/workflows-releases/releases/latest/download/install.ps1 | iex
```

Open a new terminal, then run `runboo`.
The application includes its runtime. Node.js and Rust are not needed.

Installers check archive and file checksums before activating a version.
Each release also provides checksums, build provenance, and dependency notices.
You can inspect the installer from the release before running it.

## Downloads

Choose your operating system and CPU architecture from the release assets.
Extract the complete archive into one directory, then run `runboo` or `runboo.exe`.
Keep the included application files together.

The Linux build requires kernel 5.1 or newer.
Release checks cover current Linux, macOS, and Windows CI systems.
Older system versions may need further testing.

## Updates and rollback

Run the installation command again to select the latest stable release.
To select an earlier version or a release candidate, use the installer link on that release page.

Existing sessions keep running through local server restarts.
Keep older installation directories while their sessions remain active.
Closing the interface leaves sessions running. End sessions inside the application when you no longer need them.

For available commands, run `runboo --help`.
