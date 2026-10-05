# Textly release history

## 0.1.1

- Textly accepts arbitrary file types through Open With, including extensionless files. For unfamiliar extensions, use Open With → Other → Textly. Opening uses text contents rather than a filename whitelist.
- Repair Finder opening accepts unknown extensions and extensionless text. It preserves or creates the selected file's Textly binding so subsequent double-clicks open the editor, and backs up metadata before removing the document's download restriction.
- Repair no longer changes this Mac's default editor for other files.
- Binary control data is rejected even when it has no NUL bytes or carries a Unicode BOM. Named pipes are rejected without blocking the repair picker.
- Native verification covers arbitrary filenames, UTF-16 text, selected-file repair and default OS file opening after repair.

## 0.1.0

Initial Textly release for team use, distributed through this official download repository.

- Independent app name, T icon, `com.hydakyo.textly` identity, preferences and draft storage.
- Universal executable for Apple Silicon and Intel, requiring macOS 15 or later.
- Native macOS text-editing interface, document tabs, local recovery and Find/Replace.
- New drafts suggest a `.txt` filename; a bare name is saved with `.txt`. Existing filenames and explicitly chosen extensions are preserved.
- Closing the window keeps the app alive; reopening from Dock preserves the workspace.
- Finder file opening, Unicode editing, external file changes and atomic saving.
- DMG and ZIP installers, build metadata and SHA-256 checksums.

This distribution uses an ad hoc signature and is not Apple-notarized. Runtime testing was performed on Apple Silicon; Intel compilation is verified, Intel hardware testing is not.
