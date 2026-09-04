# Bandwidth

VB6 systray and desktop bandwidth monitor (`CS Bandwidth Monitor.exe`) built on IP Helper / netstat wrappers (`CIpHelper`, interface classes) with settings, stats, and colour UI forms.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Bandwidth` (`Bandwidth.vbp`) | VB6 | WinForms exe | Bandwidth |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Bandwidth.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCTL.OCX`
  - `comdlg32.ocx`
- IP Helper / network APIs available on the target Windows host

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Bandwidth`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
