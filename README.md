# Pantheon — Releases

This repository hosts public release artifacts for **Pantheon**, a development toolkit for VRChat, Unity, and Blender creators.

> Source code: [sylvanas-labs/pantheon](https://github.com/sylvanas-labs/pantheon) *(private)*

## Important: AI Access Warning

**Pantheon is designed to work with AI coding assistants** (Claude Code, OpenAI Codex, etc.) that have access to your computer. When fully configured, Pantheon provides AI agents with the ability to:

- **Read and modify Unity scenes** — create, move, delete GameObjects, wire components, write scripts
- **Compile and execute code** — C# scripts in Unity, Python scripts for Blender and knowledge services
- **Build and upload to VRChat** — publish worlds and avatars to your VRChat account
- **Run Blender headless** — execute bpy scripts that create and modify 3D models
- **Create and manage projects** — create new Unity/VRChat projects, install packages
- **Access the network** — download documentation, check for updates, submit community knowledge

### Recommendations

- **Use a separate development machine** if possible. Pantheon gives AI broad access to your development environment.
- If a separate machine isn't available, **use a separate user profile** on your PC so the AI's access is isolated from your personal files.
- **Review AI actions** before approving them, especially uploads to VRChat and any file modifications outside your project directories.
- Pantheon itself does **not** collect telemetry or send data without your explicit action, but the AI assistant you pair it with operates under its own privacy policy.

## Downloads

Go to the [Releases](../../releases) tab to download the latest version.

| File | Description |
|------|-------------|
| `pantheon-setup.exe` | Windows NSIS installer (recommended) |
| `pantheon.exe` | Standalone self-contained executable |

## Release Tracks

| Track | Tag format | Description |
|-------|-----------|-------------|
| **Stable** | `v1.2.3` | Built from `main`. Recommended for production use. |
| **Beta** | `v1.2.3-beta.N` | Built from `develop`. May be unstable. |

## Installing on Windows

1. Download `pantheon-setup.exe` from the latest release
2. Run the installer — **no admin required**
3. Review the disclosure page (what Pantheon does on your system)
4. Choose whether to auto-start on login
5. Launch Pantheon and select a setup template (VRC Development, Standard Unity, etc.)

Or download `pantheon.exe` for a portable single-file installation.

## Requirements

- **Windows 10/11** (x64)
- **Python 3.11+** (for Mnemosyne knowledge service and Hermes API gateway)
- **Unity 2022.3+** (for Unity integration via Tiresias plugin)
- **Blender 4.x** (optional, for Blender integration)
- **An AI coding assistant** (Claude Code, Codex, etc.) for full functionality

## What Pantheon Does Not Do

- Does not require admin privileges
- Does not modify system files or other applications
- Does not collect telemetry, analytics, or usage data
- Does not send your project files anywhere
- Does not run AI models locally
