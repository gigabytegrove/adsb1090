![ADSB1090 Local Node](https://github.com/user-attachments/assets/c5f73f58-5dbf-44cd-8d39-aab2296ea227)

# ADSB1090 Local Node

ADSB1090 Local Node is a self-hosted ADS-B receiver, aircraft map, and local admin interface for 1090 MHz aircraft tracking.

It is built for people who want to run their own ADS-B station with a local browser-based map, receiver status, configuration tools, and optional ADSB1090 Network participation.

The local interface runs on port **8090** by default:

```text
http://localhost:8090
```

This repository is used for public ADSB1090 Local Node releases, release notes, documentation, and issue tracking. The source code is not published in this repository.

---

## Current Release

**ADSB1090 1.70 Public Beta**

Download the latest release:

[ADSB1090 Releases](https://github.com/gigabytegrove/adsb1090/releases)

Available builds:

* Windows 64-bit
* Windows 32-bit
* Linux 64-bit
* Linux 32-bit
* Linux ARMv6
* Linux ARMv7
* Linux ARM64

---

## Features

* Local ADS-B aircraft map
* Browser-based admin interface
* Receiver setup and status
* Aircraft list and detail views
* Coverage and reception tools
* Traffic replay
* Local RTL-SDR receiver support
* Compatible remote source support
* Map and admin appearance options
* Optional ADSB1090 Network participation

---

## Hardware

A typical local setup uses:

* Supported RTL-SDR USB receiver
* 1090 MHz antenna
* Windows or Linux system
* Browser access to the local interface
* Internet access if optional Network features are enabled

Remote aircraft data sources may also be used where supported.

---

## Installation

Download the correct package for your system from the releases page, extract it, and run ADSB1090.

### Windows

1. Download the Windows build for your system.
2. Extract the ZIP file.
3. Run the ADSB1090 executable.
4. Allow local network access if Windows Firewall prompts you.
5. Open:

```text
http://localhost:8090
```

### Linux

1. Download the Linux build for your system architecture.
2. Extract the release package.
3. Make the binary executable if needed.
4. Run ADSB1090.
5. Open:

```text
http://localhost:8090
```

Example:

```bash
unzip ADSB1090-*.zip
cd ADSB1090-*
chmod +x adsb1090
./adsb1090
```

Package names may vary by release. Check the release notes for the version you downloaded.

---

## Updating

Before updating, back up your current ADSB1090 folder, configuration, and local data.

General update process:

1. Stop ADSB1090.
2. Back up the current folder.
3. Download the new package for your platform.
4. Extract the new release.
5. Start ADSB1090.
6. Open the local admin interface at `http://localhost:8090`.
7. Confirm receiver, map, appearance, and Network settings.

---

## ADSB1090 Network

ADSB1090 Network participation is optional.

The local node can be used without joining ADSB1090 Network. If Network features are enabled, they are controlled by the node owner through the local interface and official ADSB1090 systems.

Public release builds may include Network client features intended only for authorized ADSB1090 nodes using valid credentials.

Do not attempt to reverse engineer, clone, bypass, emulate, scrape, overload, or connect unauthorized software to ADSB1090 Network services.

---

## Privacy and Security

Do not post private tokens, configuration files, logs, internal URLs, credentials, or personally identifying receiver details in public issues, screenshots, discussions, or support requests.

Do not expose the ADSB1090 admin interface directly to the public internet unless it is properly protected.

---

## Issues

Public issues are for non-sensitive bug reports, release feedback, documentation problems, and general local-node support.

Helpful details include:

* ADSB1090 version
* Operating system
* System architecture
* Receiver hardware
* Steps to reproduce the issue
* Non-sensitive log excerpts
* Screenshots with private information removed

Do not post private tokens, credentials, full configuration files, internal API details, private Network details, or unredacted logs.

---

## Source Code and Licensing

ADSB1090 Local Node is distributed publicly as release builds. The source code is not published in this repository.

Unless a separate written license is provided by Gigabyte Grove, no permission is granted to copy, modify, redistribute, reverse engineer, repackage, resell, or create derivative works from ADSB1090, its release packages, Network integration behavior, or related project materials.

All rights are reserved by Gigabyte Grove.

---

## Disclaimer

ADSB1090 is intended for hobbyist, educational, and informational aircraft tracking use.

It is not a certified aviation system, flight safety system, navigation system, ATC system, dispatch system, or emergency response tool.

Aircraft data may be incomplete, delayed, inaccurate, or unavailable.

---

## About

ADSB1090 is developed by Gigabyte Grove.
