# SUVADI-OS v1.0

A fake command-line operating system that runs entirely in the browser — CRT phosphor glow, a typed boot sequence, a joke-filled virtual filesystem, and a couple of easter eggs.

## Description

SUVADI-OS is a single-file HTML toy that pretends, convincingly, to be a terminal. There's no real filesystem, no real shell, no backend — just a JavaScript object standing in for a directory tree and a command parser reading your keystrokes. The whole thing is built to feel like an old CRT monitor: authentic phosphor green, scanlines, a screen flicker, and a boot sequence that types itself out character by character before handing you the prompt.

It exists purely for the fun of it — no production purpose, no data collection, nothing to configure. Open it, type `help`, and start poking around.

## Visuals

- **Boot sequence** — an ASCII logo and a typed-out startup log before the prompt appears
- **CRT shell** — scanlines, vignette, a subtle power-on flicker, phosphor-green glow on all text
- **Virtual filesystem** — `/home/guest`, `/jokes`, `/secrets`, and a hidden `.hidden/` folder for anyone who thinks to run `ls -a`
- **Matrix easter egg** — a full falling-code overlay triggered by the `matrix` command

## Installation

No installation needed. It's a single self-contained HTML file — open it directly in any modern browser. No server, no build step, no dependencies beyond a Google Font loaded at runtime.

## Usage

Type `help` at the prompt to see the full command list. A few highlights:

- `ls [-a] [path]` and `cd [path]` — move around the fake filesystem
- `cat <file>` — read a file's contents
- `fortune` — get a random piece of unsolicited, semi-relatable wisdom
- `neofetch` — fake system info with ASCII art
- `sudo <anything>` and `exit` — both refuse you, in character
- `matrix` — falling code overlay; press any key or click to return
- Up/down arrows cycle through command history, like a real shell

Nothing you type is stored anywhere outside the current browser tab — refreshing the page resets everything.

## Support

Personal single-file build, not a maintained package — no support channel. For new commands, jokes, or filesystem entries, describe what's wanted and a new version can be generated.

## Roadmap

Ideas for a future pass, not yet built:
- More filesystem entries and jokes to discover
- Additional easter-egg commands
- A `man <command>` page for each command, for extra flavor

## Contributing

Personal project — not open for external contributions. Feedback and change requests are welcome directly.

## Authors and acknowledgment

Built as a purely-for-fun entry in the ongoing series of single-file creative builds.

## License

Personal-use project. No license currently applied.

## Project status

Active — first working version complete.
