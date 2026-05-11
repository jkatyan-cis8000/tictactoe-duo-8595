# ARCHITECTURE.md

Written by team-lead before spawning teammates. This is the shared blueprint —
teammates read it to understand what they are building and how their module fits.
Update it when the structure changes; do not let it drift from the actual code.

## Module Structure

<!-- List every planned file/module with its responsibility.
     Be specific enough that a teammate knows exactly what to build.
     Example:
       - src/board.py: 3x3 grid state, move validation, win detection
       - src/game.py: turn management, player state, game loop
       - src/ui.py: terminal rendering, user input parsing
-->

## Interfaces

<!-- How modules communicate. List the key functions/classes each module exposes
     and what other modules depend on them. This is the cross-cutting contract
     that prevents integration failures between independently-working agents.
     Example:
       - board.py exposes: Board class with is_valid(row, col) -> bool,
         apply_move(row, col, player) -> None, check_winner() -> str | None
       - game.py depends on Board; ui.py depends on Game
-->

## Shared Data Structures

<!-- Types or data formats passed between modules.
     Define these here so all agents agree on the shape before writing code.
-->

## External Dependencies

<!-- Libraries required and why each was chosen. -->
