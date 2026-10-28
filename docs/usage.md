# Usage

## Requirements

- C# / .NET 8
- Windows 10 or 11 (or the platform listed in the README)

## Install

1. Install the .NET 8 desktop runtime.
2. Download and unpack Nova.
3. Sign in with Steam Guard.
4. Select games and start the idler.
5. Set a session limit and let it run.

## Configuration

```text
%APPDATA%\Nova\
├── config.ini
├── profiles\
└── logs\
```

- Steam Guard is supported.
- Idle up to 32 games at once.
- Library export supports CSV and JSON.

## Commands

```text
# run
Nova.exe

# cli mode
Nova.exe --idle 730,440 --limit 4h
Nova.exe --export library.csv
```

## Uninstall

Delete the application folder and `%APPDATA%\Nova`. No services, no
drivers, no scheduled tasks are installed.