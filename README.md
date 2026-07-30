# Board Game Collection Manager - Board Game Collection Manager 2026

> **A responsive web catalog for managing board games, saving personal ratings and notes, and accessing your collection across devices with optional GitHub synchronization.**

[![Platform](https://img.shields.io/badge/Platform-Web%20Browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexhillnht9470/board-game-collection-hub?style=flat-square)](https://github.com/alexhillnht9470/board-game-collection-hub)

---

<p align="center">
  <a href="https://alexhillnht9470.github.io/board-game-collection-hub/">
    <img src="https://img.shields.io/badge/Download-Board%20Game%20Collection%20Manager%20Latest-brightgreen?style=for-the-badge" alt="Download Board Game Collection Manager">
  </a>
</p>

> **[Download Board Game Collection Manager](https://alexhillnht9470.github.io/board-game-collection-hub/)**

---

[Download Latest Build](https://alexhillnht9470.github.io/board-game-collection-hub/)

---

## Overview

Board Game Collection Manager is a responsive browser application for building and maintaining a personal board game library. Games can be entered by hand or imported from a BoardGameGeek URL, then supplemented with notes, a thumbs up or thumbs down rating, images, and other collection information.

The application works in desktop and mobile browsers. Your catalog is saved locally in browser storage, with optional GitHub backup and synchronization for access across devices. GitHub Gist sharing also lets you publish a view-only version of the collection.

---

## What You Can Do

- Create, update, and delete board game records
- Populate game information from BoardGameGeek URLs
- Add personal notes and thumbs up or thumbs down ratings
- Narrow the collection using the available game attributes
- Manage multiple images with IndexedDB caching
- Keep the main catalog in local browser storage
- Back up and synchronize data with GitHub
- Publish a read-only collection through GitHub Gist
- Use the responsive interface on desktop and mobile devices

---

## Installation

### Use the published web app

1. Visit the [latest build](https://alexhillnht9470.github.io/board-game-collection-hub/).
2. Open it in a modern web browser.
3. Add games manually or import them from BoardGameGeek.

### Serve the project locally

Download the repository and run the files through a local static web server:

```bash
git clone https://github.com/alexhillnht9470/board-game-collection-hub.git
cd REPO
```

After starting your preferred local web server, open the address it displays. Running the application through a server provides more consistent browser storage and application behavior.

---

## Getting Started

1. Launch the app in a desktop or mobile browser.
2. Enter a board game yourself or submit its BoardGameGeek URL for importing.
3. Add notes, a personal rating, and any extra images to the record.
4. Apply collection filters to find games using their available attributes.
5. Update the catalog as your board game collection develops.
6. Enable GitHub backup and synchronization when you need the catalog on multiple devices.
7. Generate a view-only GitHub Gist share for collections that should be visible without edit access.

---

## Data and Service Settings

The main collection lives in browser storage, meaning each browser profile has its own local catalog. Images are cached through IndexedDB.

GitHub backup, synchronization, and Gist sharing are set up inside the application when required. Check the available settings before linking your collection to a GitHub service.

---

## Requirements

- A modern web browser
- JavaScript enabled
- A desktop or mobile device that supports browser storage
- Enough browser storage for the catalog and cached images
- Internet access for BoardGameGeek imports and GitHub features
- Sufficient space for the collection size and its image galleries

---

## Frequently Asked Questions

### Is the app usable on a phone?

Yes. Its responsive layout supports both mobile and desktop browsers.

### Where does the catalog live?

The catalog is saved locally in browser storage, while cached images are stored with IndexedDB.

### How can I import a game from BoardGameGeek?

Start the import process and enter the game's BoardGameGeek URL. The application uses that address to fill in the available game information.

### Can I access the catalog from a different device?

Yes. GitHub backup and synchronization can be used to transfer collection data between devices. The local browser catalog remains distinct from the synchronized copy.

### Is there a way to share the collection without edit permissions?

Yes. GitHub Gist sharing creates a view-only collection link.

### What if an import does not include all the information I need?

Open the imported game and make the missing changes manually. Notes, ratings, and other entry details can be added or adjusted afterward.

### Could clearing browser data delete my local collection?

Yes. Since the catalog is held in browser storage, clearing site or browser data can remove the local copy. Use the GitHub backup workflow when you need another copy of the collection.

### Where can I find the newest version?

Open the [latest build](https://alexhillnht9470.github.io/board-game-collection-hub/) to use the current published release.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
