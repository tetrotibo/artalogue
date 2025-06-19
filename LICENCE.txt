# ARTALOGUE | Etsy Cataloging & Upload Assistant

Artalogue is a FileMaker-based utility developed to assist artists and gallery owners in cataloging artworks and streamlining the listing process on platforms like Etsy.

As a designer with both technical and artistic sensibilities, I needed a way to organize detailed painting metadata and transfer it efficiently into e-commerce platforms. Existing solutions felt either too generic or too inflexible so I designed Artalogue as a semi-automated bridge between a clean structured database and the Etsy listing form.

Built with FileMaker Pro 19, it combines precise encoding, intuitive dropdown inputs and form automation tools to simplify the workflow of publishing an artwork online.

<img src="https://github.com/tetrotibo/artalogue/blob/main/screenshots/a_dashboard_01.png?raw=true" style="max-width: 100%;" alt="Artalogue Screenshot">

<p align="center">
  <a href="https://www.youtube.com/watch?v=dummy-link">
    <img src="https://img.shields.io/badge/VIDEO%20DEMO-5c7fa3?style=for-the-badge&logo=youtube&logoColor=white" alt="VIDEO DEMO">
  </a>
</p>

## Project Presentation

The user begins by manually encoding essential artwork attributes into Artalogue's database. These include painting style, title, price, creation date, dominant colors, shape, canvas material and more. This step ensures that every piece is described with precision and consistency.

During this process, Artalogue also generates a unique product serial number for each artwork. The serial is automatically built based on the creation date and the painting technique used, allowing for fast identification and internal tracking.

Once encoding is complete, the user triggers a semi-automatic syncing procedure. Artalogue then transfers the data into the appropriate fields of the Etsy listing form via scripted automation, reducing the risk of typos and saving time. In addition to textual metadata, Artalogue also uploads the selected artwork images and video previews directly to the listing, avoiding the need for manual media uploads. The syncing process supports formatting adjustments where necessary to meet Etsy’s character limits and input expectations.

The overall goal is to retain full control of metadata entry while eliminating the tedious copy-paste process between database, media folders and web browser.

## Built With

- FileMaker Pro 19 – custom database application
- MBS plugin (MonkeyBread Software)
- JavaScript
- AppleScript

## Features

- Artwork metadata encoding with dropdown-driven consistency
- Automatic generation of unique serial numbers based on technique and creation date
- Semi-automated Etsy listing population including image and video uploads
- Media manager with custom export resolutions and formats
- Visual clarity and fast onboarding for artists and non-tech-savvy users

## Licensing
Application, screenshots and demo video are all original works and protected.  
See [LICENCE.txt](https://github.com/tetrotibo/artalogue/blob/main/LICENCE.txt) for details regarding code and media usage rights.
