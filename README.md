# Mariah Oxley — portfolio site

A hand-built copy of my Squarespace site. No frameworks or build tools: just
files a web browser can open directly.

## What's in here

| File / folder | What it is |
| --- | --- |
| `index.html` | The **Video** page (home page). All the projects live here. |
| `about.html` | The **About** page. |
| `style.css`  | How everything looks: fonts, colors, spacing, grid layout. |
| `images/`    | The logo, my photo, and the GIF thumbnail for each project. |
| `fonts/`     | The typewriter-style font the site uses (Source Code Pro). |

## Common edits

**Add a project.** Open `index.html`, find a project similar to the new one,
copy its whole `<div class="card"> ... </div>` block, paste it where you want
it, then change the link (`href="..."`), the image file name, and the text.
Put the new GIF in the `images/` folder.

- Horizontal videos go inside a `<div class="row wide">` (3 per row).
- Vertical videos go inside a `<div class="row tall">` (4 per row).

**Change text.** Just edit the words between the `<p>` and `</p>` tags.

**Change the look.** The top of `style.css` has a short "settings" section
for colors, font, and spacing.

## Previewing

Double-click `index.html` to open it in your browser. After editing a file,
save it and refresh the browser tab.
