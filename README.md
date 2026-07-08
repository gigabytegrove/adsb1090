<img width="1913" height="905" alt="image" src="https://github.com/user-attachments/assets/c5f73f58-5dbf-44cd-8d39-aab2296ea227" />

# ADSB1090

ADSB1090 is a self-hosted ADS-B receiver, aircraft map, and local admin interface for tracking 1090 MHz aircraft traffic.

It is built for aviation hobbyists, ADS-B station owners, and operators who want a clean local aircraft tracking setup that can run on Windows or Linux with supported RTL-SDR hardware or compatible remote aircraft data sources.

ADSB1090 can be used as a standalone local receiver and map, or it can optionally participate in the ADSB1090 Network when enabled by the node owner.

## What ADSB1090 Does

ADSB1090 receives, processes, and displays aircraft position data from supported ADS-B sources. The local system provides an aircraft map, receiver controls, system status, coverage tools, replay features, and an owner-focused admin interface.

The goal is to make ADS-B receiving easier to run, easier to understand, and easier to manage without requiring every user to manually assemble several separate tools.

## Key Features

* Local ADS-B aircraft map
* Local admin interface for receiver and system management
* Support for 1090 MHz ADS-B / Mode S traffic
* Supported RTL-SDR receiver support
* Compatible remote aircraft data source support
* Aircraft list and aircraft detail views
* Coverage and reception visibility tools
* Traffic replay features
* Configurable map and admin appearance
* Windows and Linux builds
* Local-first operation
* Optional ADSB1090 Network participation
* Designed for both beginner and advanced ADS-B hobbyist use

## Common Uses

ADSB1090 can be used for:

* A home ADS-B receiver station
* A local aircraft tracking map
* A headless feed node
* A small aviation monitoring setup
* Receiver testing and coverage checks
* Personal aircraft observation
* Optional participation in a wider ADS-B sharing network

## Supported Platforms

ADSB1090 is intended to support common Windows and Linux systems, including desktop, server, and small-board Linux environments.

Available builds may vary by release. Check the latest release package for the exact platforms included.

## Supported Hardware

ADSB1090 is designed for supported RTL-SDR based receivers commonly used for 1090 MHz ADS-B reception.

A typical setup includes:

* A supported RTL-SDR USB receiver
* A 1090 MHz antenna
* A Windows or Linux system
* Reliable network access if optional network features are enabled

Remote aircraft data sources may also be used where supported.

## Local-First Design

ADSB1090 is designed to work as a local ADS-B receiver and map first.

Network participation is optional. Node owners should be able to run ADSB1090 locally without being required to publish their receiver publicly.

## Privacy

ADSB1090 is intended to give node owners control over their local receiver and optional network participation.

Do not publish private keys, tokens, configuration files, logs, internal endpoints, or personally identifying receiver details in public issues, commits, screenshots, or support requests.

## Security Notes

Do not expose the ADSB1090 admin interface directly to the public internet unless it is properly protected.

Recommended precautions include:

* Keep the host operating system updated
* Use firewall rules appropriate for your environment
* Keep private configuration files out of public repositories
* Do not share private access tokens or internal URLs
* Review screenshots before posting them publicly
* Use trusted network access for administration

## Installation

Download the latest ADSB1090 release from the repository Releases page.

After downloading the release package for your platform:

1. Extract the package.
2. Run ADSB1090.
3. Open the local interface shown by the application.
4. Complete receiver setup.
5. Open the aircraft map.
6. Adjust settings as needed from the local admin interface.

Exact setup steps may vary by platform and release.

## Updating

To update ADSB1090, download the latest release package and follow the release notes for that version.

Before updating, back up any important local configuration or data according to the instructions included with the release.

## Public Issues and Support

When opening a public issue, include only safe, non-sensitive information.

Helpful public issue details include:

* ADSB1090 version
* Operating system
* Hardware type
* Receiver type
* General problem description
* Relevant non-sensitive log excerpts
* Screenshots with private data removed

Do not include:

* Private tokens
* Internal API URLs
* Full configuration files
* Private network addresses unless necessary and sanitized
* Personally identifying station information
* Secret keys
* Credentials
* Unredacted logs containing sensitive information

## Project Status

ADSB1090 is actively developed and maintained.

Public releases are intended to provide a stable local ADS-B receiver and aircraft map experience while continuing to improve usability, reliability, platform support, and owner-facing controls.

## Disclaimer

ADSB1090 is intended for hobbyist, educational, and informational aviation tracking use.

Aircraft position data may be incomplete, delayed, inaccurate, or unavailable depending on receiver coverage, signal quality, aircraft equipment, local conditions, and data source limitations.

Do not use ADSB1090 as a primary source for flight safety, navigation, emergency response, or operational decision-making.

## License

No license is granted unless a license file is included in this repository.

If this repository does not include a license file, all rights are reserved by the project owner.
