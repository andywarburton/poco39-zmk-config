# Poco39 ⌨️

*Poco* — Italian for "a little". Because sometimes a little is exactly enough.

The Poco39 is a handwired 39-key mechanical keyboard running ZMK firmware on a Nice Nano v2. It fits neatly on your desk, asks nothing of you, and types everything you need. No numpad. No F-row. No regrets.

---

## The Board

- **39 keys** across a 4×10 matrix — the bottom row is missing one key because we decided we didn't need it and we stand by that decision
- **Nice Nano v2** microcontroller — wireless Bluetooth, USB-C, and enough flash to hold your entire personality
- **WS2812 RGB underglow** — 14 LEDs glowing green by default, because subtlety is overrated but so is going full gaming-chair-energy
- **ZMK Studio** compatible — remap keys live from your browser without reflashing

---

## Layers

| Layer | Purpose |
|-------|---------|
| 0 | Default — QWERTY, the classic |
| 1 | Numbers & symbols — top row goes 1–0, second row goes `!@#$%^&*()`, third row sneaks in `[]\` |
| 2 | Navigation — arrows on WASD, grave top-left, `+=` and `-_` top-right |
| 3 | System — Bluetooth device select, media controls, RGB controls, and the Studio unlock key |
| 4 | Reserved — for future you to fill with something inspired |

Hold the rightmost keys on the bottom row to activate layers 1, 2, and 3 respectively.

---

## ZMK Studio

To unlock the keymap for live editing:

1. Connect via USB
2. Open **[studio.zmk.dev](https://studio.zmk.dev)**
3. Hold **MO3** (bottom-right key) and tap the key next to ESC to unlock

---

## RGB Controls

While holding **MO3**:

| Key | Action |
|-----|--------|
| U | Toggle on/off |
| I | Hue up |
| O | Brightness up |
| J | Next effect |
| K | Hue down |
| L | Brightness down |

---

## Building

Firmware is built automatically via GitHub Actions on every push. Download the latest `.uf2` from the [Actions tab](../../actions).

To flash:
1. Double-tap the reset button on the Nice Nano — it mounts as a USB drive
2. Drag the `.uf2` onto it
3. It reboots and you're done

---

*Small keyboard. Big feelings.*
