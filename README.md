# Net

VB6 network administration workbench (project Project1) over NetAPI32 and MPR. Enumerates LAN servers with `NetServerEnum`, resolves domain controllers, and wraps user and local-group helpers (`NetUserAdd`/`Enum`/`GetInfo`/`SetInfo`/`ChangePassword`, `NetLocalGroupAddMembers`). A Shutdown dialog can force or abort a timed remote `InitiateSystemShutdown` against a named machine.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Project1.vbp`) | VB6 | WinForms exe | Server enum, user/group NetAPI helpers, remote shutdown |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Project1.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Windows NetAPI32 / Advapi32 privileges for remote user and shutdown calls

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Net`.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
