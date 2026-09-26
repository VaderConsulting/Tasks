# Tasks

VB6 Task Manager / BEAware (`BEAware.exe`, project `TaskMan`): lists Task Scheduler jobs on selected targets and sitelocs via the TaskScheduler type library, with New Task, a FlexGrid target list, and status updates (ADO plus Ping OCX). Open `Beaware.vbp` in the VB6 IDE.

**Source last updated:** 2001-01-11 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TaskMan` (`Beaware.vbp`) | VB6 | WinForms exe | Browse/create Task Scheduler jobs on targets |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Beaware.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft ActiveX Data Objects 2.5
- TaskScheduler 1.0 Type Library (taskscheduler.dll)
- MSFlexGrid (MSFLXGRD.OCX) and ping.ocx

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Tasks`. Project company field: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
