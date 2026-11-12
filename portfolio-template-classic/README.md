# Classic Portfolio Template

A portfolio with more sections and a light / dark mode button. Plain HTML and CSS, no JavaScript.

## Files

- `index.html` - all the text and sections
- `style.css` - colors and layout
- `images/` - placeholder pictures (replace them with yours)

## Step 1: Add your info

Open `index.html`. Search (Ctrl + F) for these and replace them:

- `Your Name` - page title, logo, heading and footer
- `Your tagline here` and `Your role or interests here`
- `description here` - short texts you need to write yourself
- Education, achievements and experience cards (`School or institution name here`, `Achievement title here`, `Role title here`)
- `you@example.com` - your email (change it in **both** the link and the visible text)
- `Your city, country` and `Your course or role`

Need more cards? Copy one whole `<article>` block and paste it under the last one in the same section.

Do not need a section (for example, Experience)? Delete that `<section>` and also its link in the `<nav>` menu.

## Step 2: Change the images

Put your pictures in `images/` and keep the same file names, or change the `src="..."` in `index.html`.

- `profile.svg` - your photo (shown in a circle, so use a square picture)
- `about.svg` - a picture for the About section
- `project-1.svg`, `project-2.svg` - project pictures (16:9)
- `certificate.svg` - certificate or award photos

JPG and PNG are fine too. Just change `.svg` to `.jpg` or `.png`. Always write a short `alt="..."`.

Tip: if you post a certificate photo, hide private details first (ID numbers, signatures, home address).

## Step 3: Change the colors

At the top of `style.css`, the first `:root` block is the **light** colors. The second block, `body:has(#theme-toggle:checked)`, is the **dark** colors. Change the values there.

```css
:root {
    --accent: #9a5b0b;  /* main color */
}
```

## Before you publish

- Remove anything you do not want strangers to see.
- Test both light and dark mode, and open the page on your phone.
