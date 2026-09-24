# AtomicIQ downloads

Official desktop installer downloads for AtomicIQ / NOLA Core.

Choose the installer for your computer:

| Computer | Download | Install |
| --- | --- | --- |
| Apple-silicon Mac, macOS 14 or later | [Mac releases](https://github.com/NOLA-AI-Inc/atomiciq-downloads/releases): open the newest release ending in `-macos` and download `Install-AtomicIQ-macOS.zip` | Extract the ZIP. Open Terminal, type `bash ` (including the space), drag the extracted `install-atomiciq.sh` into Terminal, and press Return. |
| Linux x86_64 with a systemd user session | [Linux desktop releases](https://github.com/NOLA-AI-Inc/atomiciq-downloads/releases): open the newest release ending in `-linux-desktop` and download `AtomicIQ-Linux-x86_64.run` | In a terminal, run `chmod +x AtomicIQ-Linux-x86_64.run`, then `./AtomicIQ-Linux-x86_64.run`. |

Both installers download and verify the language and Docling PDF models during installation, so the computer needs internet access for that step. The installed application runs locally without network access.

The standalone `AtomicIQ-macOS-arm64.command` asset is the payload used by the Mac setup script. If you downloaded it directly, run it with `bash AtomicIQ-macOS-arm64.command` from Terminal; this does not require `chmod +x`.

The existing combined [v2026.09.24.2 release](https://github.com/NOLA-AI-Inc/atomiciq-downloads/releases/tag/v2026.09.24.2) contains both installers. Use it until a platform-specific release appears. Future Mac and Linux desktop releases use separate tags, so GitHub's single "latest" release can point to either platform. Each release includes SHA-256 checksums. Windows builds are on hold.
