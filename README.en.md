<p align="center">
  <img src="docs/images/banner.png" alt="IberoTOR Banner">
</p>

<h1 align="center">IberoTOR</h1>

<p align="center">
<b>OSINT workspace for anonymous investigations powered by Tor Browser</b><br>
Centralized access to Onion services, Open Source Intelligence resources and privacy-focused investigation tools.
</p>

<p align="center">

<a href="README.md">🇪🇸 Español</a> | <b>🇬🇧 English</b>

</p>

<p align="center">

![Platform](https://img.shields.io/badge/Platform-Tor_Browser-7D4698?style=for-the-badge)

![OSINT](https://img.shields.io/badge/OSINT-Investigation-blue?style=for-the-badge)

![Privacy](https://img.shields.io/badge/Privacy-Enhanced-success?style=for-the-badge)

![Onion](https://img.shields.io/badge/Onion_Services-Supported-5B2C83?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Active_Development-success?style=for-the-badge)

</p>

---

# What is IberoTOR?

**IberoTOR** is an OSINT platform built around Tor Browser, providing a centralized workspace for investigations where anonymity and access to Onion services are operational requirements.

The platform combines a carefully organized homepage with curated investigation resources, allowing analysts to access both conventional Internet services and Tor-exclusive resources from a single environment.

Rather than being simply a configured browser, IberoTOR offers a structured workspace designed to improve efficiency during OSINT investigations, Threat Intelligence activities and cybersecurity research.

---

# Project Background

IberoTOR is part of the **IberOSINT ecosystem** and was created as the privacy-focused counterpart to IberoFirefox.

While IberoFirefox provides quick access to resources available through standard web browsers, IberoTOR extends this concept by integrating Onion services and investigation resources that require anonymous browsing through the Tor network.

Both applications share the same design philosophy while addressing different investigation scenarios.

---

# Design Philosophy

The development of IberoTOR is guided by five core principles:

- Centralize OSINT resources accessible through Tor.
- Support investigations requiring anonymity.
- Reduce the time needed to locate specialized resources.
- Provide a clean and organized research environment.
- Integrate seamlessly with the IberOSINT ecosystem.

---

# Use Cases

IberoTOR has been designed for investigations where privacy and anonymous access are essential.

Typical use cases include:

- Advanced OSINT investigations.
- Threat Intelligence research.
- Access to Onion services.
- Dark Web investigations.
- Verification of information published through hidden services.
- Open Source Intelligence collection.
- Cybersecurity investigations.

---

# Architecture

IberoTOR follows a modular architecture built around Tor Browser, providing investigators with a centralized workspace for accessing both traditional OSINT resources and Tor-exclusive services.

Its design combines a customized homepage, categorized resources and privacy-oriented navigation into a single environment optimized for cybersecurity investigations.

```

                 +----------------------+
                 |     IberOSINT        |
                 |      Launcher        |
                 +----------+-----------+
                            |
                            ▼
                 +----------------------+
                 |      IberoTOR        |
                 +----------+-----------+
                            |
                            ▼
                 +----------------------+
                 |  Custom Homepage     |
                 +----------+-----------+
                            |
      +---------------------+----------------------+
      |                     |                      |
      ▼                     ▼                      ▼
 Surface Web         Onion Services        OSINT Categories
      |                     |                      |
      +---------------------+----------------------+
                            ▼
                  Intelligence Gathering

```

This architecture provides a familiar workflow while extending the investigation capabilities offered by Tor Browser.

IberoTOR provides investigators with a single access point for resources distributed across both the public Internet and the Tor network, helping streamline information gathering while maintaining an organized workflow.

---

# Custom Homepage

The customized homepage is the central element of IberoTOR.

Resources are organized into categories, allowing investigators to locate specialized tools quickly without manually searching through bookmarks or external resource lists.

The interface has been designed to reduce navigation time and improve productivity during OSINT investigations.

<p align="center">
<img src="docs/images/homepage.png" alt="Homepage" width="95%">
</p>

*Customized IberoTOR homepage.*

---

# Organized Resources

Resources are grouped into logical categories to simplify navigation and improve accessibility.

Typical categories include:

- Search Engines
- DNS & Infrastructure
- Threat Intelligence
- Malware Analysis
- Dark Web Resources
- Onion Services
- Cryptocurrency
- Social Media
- Specialized OSINT Tools

The modular structure allows new categories and resources to be incorporated as the project evolves.

---

# Onion Resources

One of the defining features of IberoTOR is its integration of resources that are only accessible through the Tor network.

Instead of maintaining separate collections of Onion links, investigators can access these resources directly from the customized homepage.

Examples include:

- Onion directories.
- Hidden service search engines.
- Specialized investigation platforms.
- Privacy-oriented intelligence resources.

<p align="center">
<img src="docs/images/onion-resources.png" alt="Onion Resources" width="95%">
</p>

*Centralized access to Onion services.*

---

---

# Privacy

IberoTOR leverages the privacy capabilities provided by Tor Browser without modifying its standard behavior.

The objective is not to replace Tor Browser, but to provide investigators with a structured workspace that makes anonymous investigations more efficient and easier to manage.

---

# Key Features

- Customized OSINT homepage.
- Organized resource categories.
- Integrated search engine.
- Bookmark management.
- Resource history.
- Direct access to Onion services.
- Tor Browser integration.
- Native IberOSINT integration.
- Modular architecture.
- Designed for anonymous investigations.

Together, these features reduce the time required to locate relevant resources while maintaining an organized investigation environment.

---

# Who is IberoTOR for?

IberoTOR has been designed for professionals who regularly conduct investigations requiring anonymous access and privacy-focused research.

Typical users include:

- OSINT Analysts.
- Threat Intelligence Teams.
- DFIR Investigators.
- SOC Analysts.
- Dark Web Researchers.
- Cybersecurity Professionals.
- Independent Investigators.
- Cybersecurity Students.

---

# Screenshots

## Main Window

<img src="docs/images/banner.png" alt="Main Window">

---

## Custom Homepage

<img src="docs/images/homepage.png" alt="Homepage">

---

## Onion Resources

<img src="docs/images/onion-resources.png" alt="Onion Resources">

---

# Technologies

IberoTOR combines the privacy capabilities of Tor Browser with a customized homepage and a structured collection of OSINT resources to provide an efficient investigation environment.

| Technology | Purpose |
|------------|---------|
| Tor Browser | Anonymous web browsing |
| HTML5 | Customized homepage |
| CSS3 | User interface styling |
| JavaScript | Dynamic homepage features |
| Python | Integration with IberOSINT |
| Linux | Recommended operating system |

---

# Requirements

The recommended environment for running IberoTOR is:

- Ubuntu 24.04 LTS or later.
- Tor Browser installed.
- Recommended screen resolution of 1920×1080 or higher.
- Internet connection.
- IberOSINT Launcher (optional for full integration).

---

# Installation

IberoTOR can be used independently on Ubuntu through Tor Browser.

## Option 1 — Standalone installation

### 1. Install Tor Browser

Update the system repositories:

```bash
sudo apt update
```

Install Tor Browser Launcher:

```bash
sudo apt install torbrowser-launcher
```

### 2. Clone the repository

Clone the official IberoTOR repository:

```bash
git clone https://github.com/JSantos1990/Iberosint-Tor.git
```

Navigate to the project directory:

```bash
cd Iberosint-Tor
```

### 3. Launch IberoTOR

Open Tor Browser and load the main file of the customized IberoTOR homepage 'Index.html' from the cloned repository.

You can also access the published version of IberoTOR directly at:

https://jsantos1990.github.io/Iberosint-Tor/

IberoTOR can be used independently or as part of the IberOSINT ecosystem.

---

## Option 2 — Complete ecosystem

IberoTOR is also part of the complete IberOSINT ecosystem, together with the main launcher, Lince, the AI-powered evidence analysis application, IberOSINT IA, etc.

For information about installing the complete ecosystem, including distribution through a virtual machine in `.ova` format, please refer to the main IberOSINT repository:

https://github.com/JSantos1990/IberOSINT

---

## Recommended installation

Two alternatives are available depending on the user's needs:

**Option 1 — Standalone installation:**  
Clone this repository and use IberoTOR with Tor Browser.

**Option 2 — Complete ecosystem:**  
Refer to the main IberOSINT repository for information about the available installation and distribution options for the complete ecosystem.

---

# Configuration

IberoTOR has been designed to work with the standard configuration provided by Tor Browser.

The customized homepage automatically organizes available investigation resources and provides quick access to:

- OSINT tools.
- Onion services.
- Specialized investigation platforms.
- Search engines.
- Threat Intelligence resources.

No modifications to Tor Browser's default configuration are required to use the platform.

---

# Project Status

IberoTOR is actively maintained as part of the IberOSINT ecosystem.

Its modular design makes it easy to expand the platform with new categories, additional resources and future investigation features while preserving a consistent user experience.

The long-term objective is to provide a dedicated workspace for investigations requiring anonymous browsing and efficient access to resources distributed across both the public Internet and the Tor network.

---

## Future Development

- [ ] Additional investigation categories.
- [ ] Automatic resource updates.
- [ ] Integration of new OSINT tools.
- [ ] Enhanced search capabilities.
- [ ] Homepage customization improvements.
- [ ] Additional Onion resources.

---

# License

Copyright © 2026 Jorge Santos

All Rights Reserved.

IberoTOR is part of the IberOSINT ecosystem and has been developed as a specialized platform for OSINT investigations requiring anonymous browsing and access to Tor network resources.

The source code, documentation, images and all other resources contained within this repository are the intellectual property of the author.

No part of this repository may be copied, modified, redistributed or used, either in whole or in part, without the prior written permission of the author.

For additional information, please refer to the **LICENSE** file included in this repository.

---

# Author

## Jorge Santos

Developer of IberoTOR.

IberoTOR was created to support OSINT professionals by providing an organized investigation platform that leverages the capabilities of Tor Browser while integrating seamlessly into the IberOSINT ecosystem.

GitHub

https://github.com/JSantos1990

---

# Acknowledgements

Special thanks to the Open Source community and to every developer whose work contributes to privacy, cybersecurity research and digital investigations.

---

<p align="center">

<strong>IberoTOR</strong><br>

OSINT Workspace for Anonymous Investigations

<br><br>

© 2026 Jorge Santos · All Rights Reserved

</p>
