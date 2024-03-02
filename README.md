# NOCOOB (Advanced Chess Assistance System)

> **Warning** NOCOOB is currently in development. Expect bugs, especially on variants.

NOCOOB is an **advanced chess assistance system** (a chess cheat) which helps you make better moves with the help of a chess engine. Just install the userscript, open the NOCOOB GUI and you're good to go! No downloading needed.


* No anti-features (*e.g. ads, tracking*)
* WebAssembly chess engine (faster than regular JavaScript engines)
* Supports the most popular chess game sites (*e.g. chess.com, lichess.org*)
* Supports multiple move suggestions, move arrow markings, chess variants & fonts
* Impossible to detect (well, you can never be sure, so let's say it's *almost* impossible)

> **Note** Please be advised that the use of NOCOOB may violate the rules and lead to disqualification or banning from tournaments and online platforms. The developers of NOCOOB and related systems will NOT be held accountable for any consequences resulting from its use. We strongly advise to use NOCOOB only in a controlled environment ethically.

| [▶️ Open NOCOOB](https://incaseddevelopment.github.io/NOCOOB/) | [⬇️]

## Getting Started

Simply install the NOCOOB userscript from your private refferer & [NOCOOB GUI](https://incaseddevelopment.github.io/NOCOOB/) and a supported chess game site. Then, just start playing! 

### Arrow Meaning

| Color    | Meaning  |
|----------------------|----------------------|
| 🟩 | Best Move |
| 🟦 | Secondary Move |
| 🟥 | Enemy Move |

## Used Libraries

* [Fairy Stockfish WASM](https://github.com/fairy-stockfish/fairy-stockfish.wasm) (*the chess engine of NOCOOB*)
* [COI-Serviceworker](https://github.com/gzuidhof/coi-serviceworker) (*allowing WASM on GitHub pages, extremely important library*)
* [HackTimer](https://github.com/turuslan/HackTimer) (*bypasses browser timer throttling, it's questionable if this does anything, but it doesn't hurt to have it for now*)
* [ChessgroundX](https://github.com/gbtami/chessgroundx) (*for displaying a board on the GUI. Modified the library a bit*)
* [FileSaver](http://purl.eligrey.com/github/FileSaver.js) (*for saving the config file*)