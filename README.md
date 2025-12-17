# RFID-Based Spotify Music Player using Raspberry Pi

## Overview
This project implements an RFID-controlled music player using a Raspberry Pi.
Each RFID card is mapped to a specific Spotify playlist, allowing music playback
to be controlled by simply scanning a card.

The system provides a simple, screen-free interaction model suitable for
personal use and IoT-based media applications.

## Problem Statement
Traditional music playback systems require manual interaction through screens
or mobile devices. This project explores an alternative physical interaction
method using RFID cards to control music playback seamlessly.

## System Description
The Raspberry Pi continuously monitors an RFID reader. When a card is scanned,
its unique ID is read and matched to a predefined Spotify playlist. The system
then uses the Spotify Web API to start playback of the associated playlist.

## Technologies Used
- Raspberry Pi
- Python
- RFID Reader (MFRC522 or similar)
- Spotify Web API
- Linux (Raspberry Pi OS)

## Key Features
- RFID-based playlist selection
- Spotify API integration
- Card-to-playlist mapping
- Simple and intuitive user interaction
- Modular Python-based implementation


## Project Status
Prototype implementation completed. Code integration and cleanup in progress.

## Future Enhancements
- Support for multiple users
- Offline fallback playlists
- Web or mobile-based configuration interface
- Visual or audio feedback on card scan

