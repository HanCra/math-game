# math-game

A small math practice game for 3rd primary (Belgian French-speaking school system).
It uses big numbers and pictures and almost no words, and is built for an old iPad (Safari on iOS 15).

## What's inside

| File | What it is |
|---|---|
| `index.html` | The whole app: layout (HTML), look (CSS) and logic (JavaScript) in one file |
| `icon-180.png` | The icon shown when the page is added to the iPad home screen |

## The four games

1. **+ −**: addition and subtraction, sometimes with the missing number in the middle (`63 + ☐ = 72`)
2. **×2 :2**: doubles and halves, shown as a little "machine"
3. **× :**: times tables (2, 5, 10, then more), division written with `:` like at school
4. **Number line**: tap where a number goes, or read the number at the arrow

Each round has 10 questions. A child gets 2 tries per question. After that the answer is shown.
- 9 or 10 right on the first try: the level goes up
- 4 or fewer: the level goes down
- 💡 shows a picture hint (blocks for tens and units, or dots in groups)

**Parent settings:** press and hold the ⚙️ button for 1 second. There you can change levels or reset.
Progress is saved on the iPad itself (in the browser), not on a server.

## How hosting works (GitHub Pages)

GitHub Pages serves the files in this repository as a website:
`https://hancra.github.io/math-game/`

Every time a change is committed to the `main` branch, GitHub rebuilds the site within a minute or two.
You can see the history of every change under **Commits**.

To try it on a computer, just open `index.html` in a browser. The keyboard works too (digits, Enter, Backspace).
