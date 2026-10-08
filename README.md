# A Plus Master Jeon Tae Kwon Do

Website for A Plus Master Jeon Tae Kwon Do, 23 West Main St, Chester, NJ 07930.

Live site: https://sergiuscommodus.github.io/master-jeon-tkd/

A single static page (`index.html`) with no build step, hosted on GitHub Pages. Any change pushed to `main` goes live in about a minute.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: layout, styles and scripts |
| `images/class-photo.jpg` | Class photo used in the hero and program cards |
| `audio/intro.mp3` | Intro music |

## Editing

| What | Where in `index.html` |
| --- | --- |
| Class schedule | the `<table id="tt">` in the Schedule section |
| Pro Shop items and prices | the `products` array in the script at the bottom |
| Hours, phone, address | the Contact section and footer |
| Grand Master bio and awards | the Instructor section |

## How the intro music works

Browsers block sound until a visitor interacts with the page. The intro tries to play the music right away. If the browser blocks it, the intro shows an "Enter the Dojang" button, and one tap starts the music and opens the site. The round button in the bottom left corner mutes or replays it. Returning visitors in the same browser session skip the intro.

## Still to add

- Real class schedule (current times are examples)
- Portrait of Grand Master Jeon (Instructor section placeholder)
- Merch photos and real prices (Pro Shop placeholders)
- A form service (for example Formspree) so the free class form and shop orders send email
- Confirm the school has the rights to use the intro music on a public site
