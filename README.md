# Platypus

A personal options-research and paper-trading tool, run by its author on his own machine.

Platypus scans a fixed universe of tickers each trading day, applies a written rulebook to
rank option contracts, and produces a daily report. It maintains paper-trading books only —
no orders are ever placed with a broker and no real money is involved.

## Google Drive access

Platypus files its own daily reports into the author's Google Drive as Google Docs. It
requests the `drive.file` scope, which grants access only to files the application itself
creates. It cannot read or modify anything else in the Drive account.

This application has a single user, its author. It is not offered as a service.

See the [privacy policy](PRIVACY.md).
