# Games 4 Ed

Free browser educational games for kids. No ads, no accounts, no tracking.

## How the site is organized

```
index.html                     the homepage with a card for each game
assets/                        screenshots used on the homepage cards
games/number-blasters/index.html
games/number-rally/index.html
games/number-knight/index.html
games/loop-lab/                music maker; index.html plus files that let it install on phones and work offline
```

Each game is one self-contained HTML file. The site is static, so GitHub Pages serves it as-is with no build step.

## Adding a new game

1. Put the game in `games/<game-name>/index.html`. It needs a normal `<!doctype html>` page with a `<meta name="viewport">` tag.
2. Add a "← All games" link back to `../../` somewhere on its start screen.
3. Add a screenshot to `assets/` and a new card to the `.games` list in `index.html`.

## Updating a game

Edit that game's `index.html` and push. The live site updates about a minute later.
