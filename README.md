# Pass the Fear — Save Manager

A powerful save management and backup protection tool for **Pass the Fear**.

Create backups, restore saves, manage multiple profiles, and protect your progress from accidental loss or corrupted save files.

> 🚧 **Work in Progress** — The project is currently under active development.

## ✨ Features

## 💾 Save Management

Manage your game saves in one place.

* View all available saves
* Switch between save profiles
* Rename saves
* Duplicate saves
* Delete unwanted saves
* Import and export saves
* View save information

## 🛡️ Backup Protection

Protect your progress automatically.

Features:

* Automatic save backups
* Manual backup creation
* Backup history
* Restore previous versions
* Backup scheduling
* Backup validation

Example workflow:

```text
Game Save Detected
        ↓
Create Backup
        ↓
Validate Save
        ↓
Launch Game Safely
```

## 🔄 Restore System

Quickly recover your progress.

* Restore latest backup
* Restore selected backup
* Compare save versions
* Preview backup information
* Safe restore process

Example:

```text
Current Save
      │
      ▼
Backup History

✓ Today 18:42
✓ Today 15:20
✓ Yesterday 22:10

[ Restore Selected ]
```

## 📊 Save Information

View detailed save statistics:

```text
Save Profile

Name: Main Progress
Progress: 68%
Playtime: 24h 17m
Save Size: 4.8 MB
Last Modified: Today 18:42
Status: Healthy ✓
```

## 🗂️ Profile Management

Create different save profiles:

* Main playthrough
* Testing profile
* Challenge runs
* Backup archives
* Experimental saves

## 🔍 Save Validation

Detect possible save problems:

* Missing files
* Invalid structure
* Corrupted data
* Incomplete backups
* Unexpected changes

Example:

```text
Save Validation

✓ File structure
✓ Data integrity
✓ Backup compatibility

Status: Safe
```

## ⚙️ Settings

Customize the application:

* Backup frequency
* Backup location
* Automatic cleanup
* Maximum backup count
* Notification settings
* Theme selection

## 🛠️ Planned Features

### Phase 1 — Foundation

* [x] Project architecture
* [x] Save detection system
* [x] Save data model
* [x] Backup system
* [x] Restore system

### Phase 2 — Save Manager

* [x] Save profiles
* [x] Save information viewer
* [x] Import / Export
* [x] Save duplication
* [x] Save organization

### Phase 3 — Protection System

* [x] Automatic backups
* [x] Backup history
* [x] Save validation
* [x] Corruption detection
* [x] Safe restore workflow

### Phase 4 — Advanced Tools

* [x] Save comparison
* [x] Backup compression
* [x] Cloud backup support
* [x] Backup scheduler
* [x] Advanced diagnostics

### Phase 5 — Community Features

* [x] Shareable backup packages
* [x] Save migration tools
* [x] Community profiles
* [x] Backup templates

## 🏗️ Technology

Built with:

* **C#**
* **.NET**
* **Avalonia UI**

Architecture:

```text
PassTheFear.SaveManager/

├── SaveManager.App/
├── SaveManager.Core/
├── SaveManager.Backup/
├── SaveManager.Storage/
├── SaveManager.UI/
└── SaveManager.Tools/
```

## 📁 Project Structure

```text
Pass-the-Fear-Save-Manager/
│
├── src/
│   ├── SaveManager.App/
│   ├── SaveManager.Core/
│   ├── SaveManager.Backup/
│   ├── SaveManager.Storage/
│   └── SaveManager.UI/
│
├── tests/
│
├── docs/
│
├── assets/
│
├── README.md
├── LICENSE
└── .gitignore
```

## 🚀 Getting Started

### Requirements

* .NET SDK
* Git
* Supported desktop platform

### Build

```bash
dotnet build
```

### Run

```bash
dotnet run --project src/SaveManager.App
```

### Run Tests

```bash
dotnet test
```

## 🗺️ Roadmap

```text
Save Detection
       ↓
Backup System
       ↓
Restore System
       ↓
Save Validation
       ↓
Advanced Diagnostics
       ↓
Community Tools
```

## 🤝 Contributing

Contributions are welcome.

You can help by:

* Reporting bugs
* Suggesting features
* Improving documentation
* Adding tests
* Improving backup algorithms
* Submitting pull requests

## ⚠️ Disclaimer

This project is an independent community-made tool.

It is **not affiliated with, endorsed by, or sponsored by the developers or publishers of Pass the Fear**.

All game-related names, assets, and trademarks belong to their respective owners.

## 📄 License

This project is licensed under the **MIT License**.

See [`LICENSE`](LICENSE) for details.
