# Textly data handling

Textly is a local text editor. Editing does not require an account or network service.

Files you open are read locally. Their contents are written only when you choose Save. Draft recovery stores documents locally in `~/Library/Application Support/Textly/session.json`. The recovery snapshot is unencrypted text, so protect your macOS account and disk if documents contain sensitive information.

Settings are stored in the app's own macOS preferences. The app watches changes to files you have opened. It does not automatically send document contents to a remote service.

Diagnostics run locally and may produce reports and screenshots. Review these files before sharing them. When reporting a problem, use a sample with personal or confidential information removed.

If you choose a Finder repair action, metadata backups are kept locally under `~/Library/Application Support/Textly/FinderRepairs/`. Normal file opening does not run that repair automatically.

Downloads and issue reports hosted on GitHub are governed separately by GitHub's own data handling policies. Do not post private documents in public issues.
