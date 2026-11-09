# Arkistai

Arkistai is a Windows application for running a shop: items, stock, customers, suppliers, sales and purchases, with a local PostgreSQL database.

This repository holds no source code. It publishes the builds under **Releases**.

## Status

Alpha. Builds are for a test PC only, not for a shop's real data. Upgrading from one alpha to the next is not supported yet.

## Getting it

1. Open **Releases** and download `…-win64.zip` from the newest release. Don't use the "Source code" links: GitHub adds them to every release, and here they hold only this README.
2. Unpack it and follow `README.txt` inside. In short, you install PostgreSQL 15 or newer, run `setup-database.bat` once, then start the program.

Windows 10 (1809 or later) or Windows 11, 64-bit; a screen of at least 1366 x 768.

## Reporting a problem

Open an issue and attach the newest file in `%LOCALAPPDATA%\Arkistai\logs`. Please don't attach a database or anything holding real customer data.

## Licence

(c) 2026 Nightkiln. All rights reserved. The program is not open source.

The third-party libraries it ships with (Qt, the PostgreSQL client, OpenSSL and others) are under their own licences. `licenses/NOTICE.txt` lists them, with each licence's text and source link.
