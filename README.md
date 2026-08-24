# RiftCity Circuit Safe — Unique Safe Template Set

This prototype uses three unique neutral safe templates:

- `assets/circuit-board-3.png` — 3 sockets on the left + 3 on the right
- `assets/circuit-board-4.png` — 4 sockets on the left + 4 on the right
- `assets/circuit-board-6.png` — 6 sockets on the left + 6 on the right

## Runtime behavior

- The artwork stays neutral/monochrome.
- Wire/socket colors are added by JavaScript at runtime.
- Matching order is randomized each new safe.
- The blank top panel in each safe is used for live timer/info text.
- Socket overlay coordinates are separately tuned for each unique safe image.
- Existing short-circuit, mistakes, timer, wire animation, and unlock behavior remain active.
