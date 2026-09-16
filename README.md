# Inline Diagnostics

Fixit Pro brings inline diagnostics and quick error solutions directly
into your editor so you can understand and fix problems faster.

Works with JavaScript, TypeScript, and other languages.

## Features

- ✗ Errors in red — inline, right on the line
- ⚠ Warnings in orange
- ℹ Info in blue
- 💡 Hints in green
- Only the highest-severity message per line is shown (no clutter)
- Toggle on/off via Command Palette

## Usage

Just install and open `.ts`, `.tsx`, `.js`, `.jsx`, or any other file. Diagnostics appear automatically.

**Toggle:** Open Command Palette (`Ctrl+Shift+P`) → `Inline Diagnostics: Toggle On/Off`

## Settings

| Setting | Default | Description |
|---|---|---|
| `inlineDiagnostics.enabled` | `true` | Enable/disable the extension |
| `inlineDiagnostics.maxMessageLength` | `80` | Max chars per message |
| `inlineDiagnostics.fontSize` | `0.85em` | Font size of inline text |
| `inlineDiagnostics.errorColor` | `#ff6b6b` | Color for errors |
| `inlineDiagnostics.warningColor` | `#ffa94d` | Color for warnings |
| `inlineDiagnostics.infoColor` | `#74c0fc` | Color for info |
| `inlineDiagnostics.hintColor` | `#a9e34b` | Color for hints |
| `inlineDiagnostics.enabledSeverities` | `[0,1,2,3]` | Which severities to show |

## Publishing

```bash
npm install
npm run compile
npm run package     # creates .vsix
npm run publish     # publishes to marketplace (needs vsce login)
```
