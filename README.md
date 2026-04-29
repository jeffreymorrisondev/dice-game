# Dice Score Sheet

A digital dice game score sheet, inspired by Yahtzee. Implemented in a single HTML file using [_hyperscript](https://hyperscript.org/)

All behavior is handled with _hyperscript via `_="..."` attributes. Score calculations, subtotals, bonus logic, and reset behavior all live directly in the markup -- no custom JS required.

## What it does

* Tracks upper and lower section scores via user input
* Calculates the upper subtotal and applies the +35 bonus at 63+
* Computes the grand total
* Resets the sheet with a “New Game” button

## Running it

Open `index.html` in a browser.

## Why Hyperscript

This is a small proof of concept. For this level of state and logic, Hyperscript is enough on its own. It will be enhanced later with fixi.js for persistence.

## Assets

Favicon uses emoji graphics from Twemoji (Twitter), provided via favicon.io.

Copyright 2020 Twitter, Inc and other contributors.

Licensed under Creative Commons Attribution 4.0:
<https://creativecommons.org/licenses/by/4.0/>
