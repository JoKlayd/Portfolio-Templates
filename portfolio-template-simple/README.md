# Simple Portfolio Template

A one-page portfolio. Plain HTML and CSS.

## Files

- `index.html` - all the text and sections
- `style.css` - colors and layout
- `images/` - placeholder pictures (replace them with yours)

## Step 1: Add your info

Open `index.html`. Search (Ctrl + F) for these and replace them:

- `Your Name` - appears in the page title, logo, heading and footer
- `description here` - short texts you need to write yourself
- `Interest here`, `Skill name here`, `Project title here`, `Category here`
- `you@example.com` - your email (change it in **both** the link and the visible text)
- `Your city, country` and `Your course or role`

Need more skills or projects? Copy one whole `<div class="skill-card">` or `<article class="project-card">` block and paste it under the last one.

Delete the line `Replace the image above with...` (class `project-note`) when you are done.

## Step 2: Change the images

Put your pictures in `images/` and keep the same file names, or change the `src="..."` in `index.html`.

- `profile.svg` - your photo (square works best)
- `project-1.svg` to `project-4.svg` - project pictures (wide, 16:9 works best)

JPG and PNG are fine too. Just change `.svg` to `.jpg` or `.png` in the `src`.

Always write a short `alt="..."` that describes the picture.

## Step 3: Change the colors

At the top of `style.css` there is a `:root` block. Change the values there and the whole site changes.

```css
:root {
    --accent: #0f766e;       /* main color */
    --accent-hover: #115e59; /* darker color (header) */
}
```

## Before you publish

- Remove anything you do not want strangers to see (phone number, home address, ID photos).
- Open the page on your phone to check it.
