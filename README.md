# ERPNext 2 QB - releases

Installers for **ERPNext 2 QB** by [Cecypo.Tech](https://cecypo.tech): a one-way daily sync of ERPNext
sales, purchases, payments and journals into QuickBooks Desktop (2018 or newer).

## Install
Download `ERPNext2QB_Setup_<version>.exe` from the [latest release](../../releases/latest) and run it.
It installs for the current Windows user (no administrator rights needed) - run it as the same user
that uses QuickBooks, and do **not** run QuickBooks as administrator.

Each installer has a matching `.sha256` file. To verify: `certutil -hashfile ERPNext2QB_Setup_<version>.exe SHA256`.

## Updates
The app checks this repository for a newer release when it starts and offers to install it
(or: About > Check for updates, or `erpnext2qb-cli update --install`). Updates are verified against the
published SHA-256 before they run. Settings, the export ledger, logs and backups live in
`%LOCALAPPDATA%\ERPNext 2 QB` and are never touched by updates or uninstall.

Support: [cecypo.tech/contact](https://cecypo.tech/contact)