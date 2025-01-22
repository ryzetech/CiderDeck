
# CiderDeck

CiderDeck is a plugin for the Elgato Stream Deck that allows you to control your music and show what your currently listening to at a click of a button.

## Description

Using CiderDeck you can do the following

- Show currently playing song's album art.
- Show currently playing song's name.
- Skip/Rewind
- Play/Pause
- Shuffle
- Repeat
- Change Volume
- Like/Dislike
- Add to Library
- and much more to come.

## Features
- Written in JavaScript
- Cross-Platform (macOS, Windows)

## Requirements
- [Cider 2.5.2+](https://cider.sh)
- Stream Deck (MK.1, MK.2, SD+, XL)
- Computer running Windows or macOS

## Changes in this fork
- modified tap behavior to accept play/pause requests instead of clicking the dial
  - did this to make toggling playback possible when using a dial stack
