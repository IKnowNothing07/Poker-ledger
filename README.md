# ♠ Poker Ledger

A dark, phone-friendly ledger for home poker nights. No app, no login, no server.

## The problem

Home games run on chips, but money changes hands in rupees. By the end of the night
nobody remembers who rebought twice, the chip-to-cash ratio gets muddled, and
settling up turns into an argument and a calculator.

## What it does

- Set the ratio once (e.g. 1:5, so a 500-chip buy-in is ₹100)
- Add players and log every buy-in and rebuy as the game goes
- At the end, enter each player's final stack. It checks the chips add up
- See each player's net win or loss on a chart
- Get the fewest possible payments to settle everyone, and share it to the group chat

## Tech

A single `index.html` in plain HTML, CSS and JavaScript. Data is saved in the
browser's local storage, so it works offline and keeps your game if you refresh.

## Use it

Open the GitHub Pages link on your phone and add it to your home screen.
