# Passive-Drying-of-3D-Printer-Filament
A mechanism that passively dries the 3D printing filament during printing. There is no need to pre-dry the filament.
<img width="705" height="761" alt="image" src="https://github.com/user-attachments/assets/5fd08c00-696c-4dfe-88ea-9b3b40dbe7ea" />
## Concept

This project is an inline filament drying system: it dries the filament while it is being printed, so there is no need to wait for a drying cycle before starting a print.

## How it works

The fan that cools the hotend heatsink creates an air flow, which the heatsink warms up slightly. Instead of venting this warm air outside the print head, the system redirects it into the 2.85mm PTFE tube that guides the filament. The fast, warm air flows around the filament and dries it as the extruder pulls it in. The humid air then leaves the printer through a filter, if one is installed.

## Why it is faster than a dry box

A traditional dry box needs several hours to dry a spool, because moisture has to escape from deep inside the wound filament. Here, only a single strand of filament is dried at a time. At just 1.75 mm wide, moisture escapes much more easily, so drying is much faster.

## Status

This is a proof of concept and is still under development.
