# Case File 11:59

A murder-mystery birthday site for Kriti.

## Folder layout

```
index.html
style.css
script.js
robots.txt
lib/                                  handwriting, quill and confetti scripts (leave as is)
photos/
    photo1.jpeg ... photo16.jpeg      archive + polaroid board, in order
    suspects/
        thorne.jpeg                   Professor Cassius Thorne
        wren.jpeg                     Wren Ashcroft
        crumb.jpeg                    Bonnie Crumb
        odessa.jpeg                   Odessa Vale
        kriti.jpeg                    Detective Kriti
music/
    birthday.mp3                      plays from "Open the vault" onwards
videos/
    compilation.mp4                   plays after the polaroid board
```

File names must match exactly, lowercase, with `.jpeg` (not `.jpg`). Any photo that's missing shows a silhouette or a placeholder instead, so nothing breaks.

Suspect photos look best as head-and-shoulders shots with the face centred. They are cropped to a portrait frame and given a black-and-white ink filter automatically.

## Changing the words

Everything personal is in the block at the top of `script.js`, under `CONFIG`:

- `welcomeLine`: the line under "Welcome to your 30s, Detective Kriti."
- `letter`: the final letter, one paragraph per line
- `clockHint`: the P.S. pointing to the clock
- `easterEgg`: the card that opens after tapping the clock 11 times
- `photoCaptions`: the 16 archive captions, in photo order

Keep each piece of text inside its quotes. If the text itself contains an apostrophe, wrap it in double quotes, like the existing lines do.

## Testing

Progress saves in the browser. To start again from the beginning, tap the red CLASSIFIED stamp on the cover 5 times.
