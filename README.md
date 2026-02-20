# Talala

A portable local web development environment for Windows — simple, fast, and powerful.

> Install once, then move anywhere. Talala is fully portable after first-time setup.

## Download

**[Download Talala v1.0.9](https://github.com/mafiaotata/talala-releases/releases/latest)** (4.9 MB)

## Quick Start

1. Download and extract the ZIP
2. Run `Talala.exe` as **Administrator**
3. **First time only**: Setup wizard guides you — choose location, packages auto-download (~5 min)
4. Click **Start All** to launch services
5. Open `http://localhost` — you're ready!

After first-time setup, Talala is fully portable — move the folder anywhere and run directly.

## What's Included

| Package | Description |
|---------|-------------|
| Apache 2.4 | Web server with auto Virtual Hosts |
| MariaDB | MySQL-compatible database |
| PHP 7.4 / 8.1 / 8.2 / 8.3 / 8.4 | Multiple PHP versions, switch instantly |
| phpMyAdmin | Web-based database manager |
| Composer | PHP dependency manager |
| WP-CLI | WordPress command-line tool |
| Node.js | JavaScript runtime |
| Git | Version control |
| Cmder | Portable terminal emulator |

### Optional Packages (install from Packages page)

| Package | Description |
|---------|-------------|
| Nginx | Alternative web server (conflict warning with Apache) |
| Redis | In-memory data store |
| PostgreSQL | Powerful relational database (runs alongside MariaDB) |
| Mailpit | Email testing tool with web UI |
| Meilisearch | Full-text search engine |
| Python | Scripting and automation |
| mkcert | Local SSL certificates |

## v1.0.9 Highlights

- **Every package works after install** — PHP gets php.ini, tools get .bat wrappers, PostgreSQL runs initdb
- **Dashboard shows all services** — start/stop nginx, redis, mailpit, meilisearch, postgresql from Dashboard
- **Conflict warnings** — Apache vs Nginx warning in Packages UI
- **Terminal** — pre-configured with PHP, Composer, WP-CLI, Python, Node.js, Git in PATH

## Requirements

- Windows 10/11 (64-bit)
- Run as Administrator (for hosts file + services)

## Support

If you find Talala useful:

- [GitHub Sponsors](https://github.com/sponsors/mafiaotata)
- [Buy Me a Coffee](https://buymeacoffee.com/mafiaotata)

## License

[MIT License](LICENSE) - Copyright (c) 2025 mafiaotata
