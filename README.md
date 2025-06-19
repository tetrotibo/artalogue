# ARTALOGUE | Artwork Cataloging & Etsy Upload Assistant

Artalogue is a FileMaker-based utility developed to assist artists and gallery owners in cataloging artworks and streamlining the listing process on platforms like Etsy.

As a designer with both technical and artistic sensibilities, I needed a way to organize detailed painting metadata and transfer it efficiently into e-commerce platforms. Existing solutions felt either too generic or too inflexible, so I designed Artalogue as a semi-automated bridge between a clean, structured database and the Etsy listing form.

Built with FileMaker Pro 19, it combines precise encoding, intuitive dropdown inputs and form automation tools to simplify the workflow of publishing an artwork online.

## Project Presentation

The user begins by manually encoding essential artwork attributes into Artalogue's database. These include painting style, title, price, creation date, dominant colors, shape, canvas material and more. This step ensures that every piece is described with precision and consistency.

Once this encoding is complete, the user triggers a semi-automatic syncing procedure. Artalogue then transfers the data into the appropriate fields of the Etsy listing form via scripted automation, reducing the risk of typos and saving time. The syncing process supports formatting adjustments where necessary to meet Etsy’s character limits and input expectations.

The overall goal is to retain full control of metadata entry while eliminating the tedious copy-paste process between database and web browser.

## Screenshots

| Encoding Form | Etsy Sync Preview |
|---------------|-------------------|
| ![Encoding](./02.SCREENSHOTS/form-encoding.png) | ![Sync](./02.SCREENSHOTS/etsy-sync.png) |

## Demo Video

[▶ Watch the Artalogue demo](https://www.youtube.com/watch?v=YOUR_VIDEO_LINK)

## Built With

- FileMaker Pro 19 – custom database application
- Scripting Engine – for triggering sync behavior
- macOS Automation – compatibility with browser actions (tested with Safari)
- Manual data entry UX – dropdown lists, editable fields, and custom value lists

## Features

- Artwork metadata encoding with dropdown-driven consistency
- Semi-automated Etsy listing population
- Support for price formatting and multi-field syncing
- Easily extensible structure for other marketplaces or metadata types
- Visual clarity and fast onboarding for artists and non-tech-savvy users

## Licensing

- FileMaker file, screenshots, and demo video are all original works and protected.
- See [LICENSE](./LICENSE) for details regarding code and media usage rights.
