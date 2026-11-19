# remote-play-bridge

A standalone helper that receives a console's Remote Play video stream over the
local network and hands the frames to other programs (for example FlatVR).

Status: early skeleton. Nothing works yet.

## Planned scope

- Find consoles on the local network and pair with them once.
- Receive the video stream and expose the latest frame to a host program.
- Forward controller input back to the console (later step).

## What this project is not

- It does not bundle or redistribute any console firmware, keys or game content.
- It is not affiliated with or endorsed by Sony Interactive Entertainment.

## License

This project is licensed under the GNU Affero General Public License v3.0 (see
[LICENSE](LICENSE)). It is built and shipped as a separate program that host
programs run as a separate process.
