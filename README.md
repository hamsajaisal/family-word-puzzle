# Family Word Puzzle

A fun, interactive, and accessible word puzzle game. Perfect for solo players or two players taking turns on the same device.

## Features
- **Game Modes**: Single Player or Two Players.
- **Customization**: Choose grid sizes (3x3, 4x4, 5x4, 5x5) and time limits.
- **Accessibility**: Optimized for screen readers (`aria-live` announcements, keyboard navigation, and custom focus indicators).
- **Keyboard Friendly**: Navigate the grid using arrow keys and submit words with `Enter`.

## How to Play
1. Configure your game mode, grid size, and timer.
2. Click **Start Game**.
3. Select letters by clicking them or using your keyboard:
   - **Keyboard Navigation**: Use **Arrow Keys** to move between cells.
   - **Selection**: Click a letter to select it. To build a word, select adjacent letters (horizontally, vertically, or diagonally).
   - **Deselection**: Click the last selected letter again to deselect it.
   - **Submit**: Click the **Done** button or press **Enter** while navigating the grid.
4. Correct words score points based on length (10 points per letter).
5. In two-player mode, players take turns finding words. The turn switches once a player submits a valid word.

## How to Enable GitHub Pages
To play this game online:
1. Go to your repository settings on GitHub: **Settings** -> **Pages** (under Code and automation).
2. Under **Build and deployment**, set the source to **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder, then click **Save**.
4. Within a minute, your game will be live at `https://hamsajaisal.github.io/family-word-puzzle/`.
