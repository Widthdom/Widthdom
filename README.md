# Widthdom

> "To every action, there is always opposed an equal reaction." — Isaac Newton

---

## About

I build developer tools and desktop software with an emphasis on predictable behavior, inspectable output, and clear operational boundaries.

Current work centers on code intelligence, release validation, and cross-platform launcher UX.

---

## Featured Projects

### CodeIndex / cdidx

A CLI tool that indexes large codebases into a SQLite database for fast search — designed for both humans and AI agents.

- SQLite + FTS5 full-text search for instant code search
- Symbol extraction — functions, classes, imports as structured data
- Incremental indexing — only re-indexes changed files
- 25+ languages supported (C#, Python, TypeScript, Go, Rust, Java, etc.)
- MCP server for AI tools (Claude Code, Cursor, Windsurf, GitHub Copilot)
- JSON output for programmatic access

```
dotnet tool install -g cdidx
```

🔗 https://github.com/Widthdom/CodeIndex

---

### FolderDiffIL4DotNet / nildiff

A .NET global tool for comparing old/new build folders and producing review artifacts for release validation.

- Reduces false positives from .NET assembly metadata noise such as MVIDs and timestamps
- Generates Markdown, standalone interactive HTML, and JSON audit reports
- Supports semantic .NET change tables, integrity checks, review notes, and archived sign-off flows
- Designed to stay self-contained and offline-friendly for release review

```
dotnet tool install -g nildiff
```

🔗 https://github.com/Widthdom/FolderDiffIL4DotNet

---

## NuGet Packages

| Package | Description |
|---------|-------------|
| [cdidx](https://www.nuget.org/packages/cdidx) | Code indexing & search CLI tool |
| [nildiff](https://www.nuget.org/packages/nildiff) | Folder diff & release validation CLI tool |
| [FolderDiffIL4DotNet.Core](https://www.nuget.org/packages/FolderDiffIL4DotNet.Core) | Core library — file comparison, Myers diff, PE/CLR detection |
| [FolderDiffIL4DotNet.Plugin.Abstractions](https://www.nuget.org/packages/FolderDiffIL4DotNet.Plugin.Abstractions) | Plugin contracts for extending FolderDiffIL4DotNet |

---

## Projects

### Praxis
A cross-platform desktop launcher built with Avalonia and .NET.

- Command execution, search, suggestions, and quick launcher workflows
- Free-positioned launcher buttons, recent Dock, launch logging, and button editing
- SQLite-backed persistence with migration support for existing launcher databases

🔗 https://github.com/Widthdom/Praxis

---

### ubuntu-setup
Setup scripts and notes for configuring a Linux development environment.

- Environment initialization
- Tooling and configuration
- Reproducible setup process

🔗 https://github.com/Widthdom/ubuntu-setup

---

## Engineering Style

- Write clean and maintainable code
- Prefer explicit logic over hidden behavior
- Avoid unnecessary complexity and dependencies
- Keep responsibility and boundaries clear

---

## Current Focus

- Developer tooling and CLI design
- Desktop application architecture and cross-platform UX
- Release validation and review automation
- CI/CD and build pipeline design
- Static analysis and code quality improvement

---

## Tech Stack

### Languages
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)

### Frameworks / Platforms
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=flat&logo=dotnet&logoColor=white)
![Avalonia](https://img.shields.io/badge/Avalonia-Desktop-8B44AC)

### Databases
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

### Scripting / Automation
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat&logo=gnu-bash&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-217346?style=flat)
![Batch](https://img.shields.io/badge/Batch-4D4D4D?style=flat)
![VBScript](https://img.shields.io/badge/VBScript-5C2D91?style=flat)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white)
![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)

### Environment
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

### Mobile
![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
