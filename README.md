# HealthOS

HealthOS is a comprehensive desktop application designed for health and wellness management. Built with modern .NET technologies, it provides an intuitive interface for tracking personal health metrics, managing medical records, and generating professional reports.

## Features

- **Data Management**: Store and query health data using a local SQLite database.
- **Secure Authentication**: Password hashing and user security powered by BCrypt.Net-Next.
- **PDF Reporting**: Generate customizable PDF reports with PdfSharpCore.
- **Image & Chart Support**: Visualize health trends using SixLabors.ImageSharp for image processing and fonts.
- **Rich UI**: Modern WPF interface with themes and responsive design.
- **Cross-Platform Ready**: Compiled for Windows x64 (.NET 8.0).

## Prerequisites

- **Operating System**: Windows 10/11 (x64)
- **.NET Runtime**: .NET 8.0 Desktop Runtime (included in self-contained deployment)

## Quick Start

1. **Download**: Obtain the latest release from the [Releases page](https://github.com/yourusername/HealthOS/releases).
2. **Run**: Double-click `HealthOS.exe` to launch the application.
3. **First Time Setup**:
   - Create a new user account.
   - Import or enter your health data.
   - Customize dashboard widgets.

```text
HealthOS.exe
```

## Usage

### Dashboard
View key metrics at a glance: weight, blood pressure, fitness goals, medication reminders.

### Data Entry
- Log daily activities, meals, vitals.
- Upload medical images/scans.
- Set recurring reminders.

### Reports
- Generate PDF summaries (daily/weekly/monthly).
- Export charts and trends.
- Share via email or print.

### Settings
- Backup/restore database.
- Theme customization.
- Data import/export (CSV/SQLite).

## Security

- Passwords hashed with BCrypt.
- Local SQLite database encrypted options.
- No cloud dependency for privacy.

## Architecture

- **Frontend**: WPF (.NET 8.0)
- **Backend**: C# with Entity Framework or ADO.NET for SQLite
- **Libraries**:

| Library | Purpose |
| :--- | :--- |
| Microsoft.Data.Sqlite | Local database |
| BCrypt.Net-Next | Password hashing |
| PdfSharpCore | PDF generation |
| SixLabors.ImageSharp | Image processing/charts |
| SixLabors.Fonts | Typography |

## Troubleshooting

- **App won't start**: Ensure .NET 8.0 Desktop Runtime is installed.
- **Database issues**: Delete `HealthOS.db` for reset (backup first).
- **PDF errors**: Check font paths and disk space.

## Contributing

1. Fork the repository.
2. Build with `dotnet build`.
3. Submit PRs to `main` branch.

## Author and Producer

Mihir Panchal

## Acknowledgments

Built using the .NET ecosystem. Special thanks to the library maintainers.

---

*Version 1.1.8 | .NET 8.0 | Windows x64*