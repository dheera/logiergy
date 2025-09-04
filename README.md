# Logiergy
## Seamlessly move the mouse/keyboard between two mutually untrusted computers

## Why this?

This allows you to have your work PC on one monitor and personal PC on another monitor, and seamlessly move the mouse between them.

## Why not Synergy?

Synergy sends your mouse and keyboard signals across the network to the other machine. If one of those machines is your corporate-issued machine, this would be a major security flag from their point of view.

This instead does NOT rely on the network, and does NOT send mouse/keystrokes over the network connection. Instead, it uses the Logitech receiver to ask your keyboard and mouse to switch to the other machine.

This also has the added benefit that if your network is down, it will continue to work just fine.

The only downside is you do not get the clipboard functionality that Synergy has.

## Requirements

Two computers that both have Logitech receivers, paired to the same mouse and keyboard. I have only tested this with MX Keys and MX Master 3.

## How

Edit "logitech-edge-switchen.json" and run logitech-edge-switcher.
