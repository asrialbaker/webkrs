# KRS Travel website

The active website is in `site-live/`. Edit this folder, including
`site-live/haji.html`, to update the preview.

## Preview on this computer

From the project folder, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1 --directory site-live
```

Open http://127.0.0.1:8000/ and refresh the browser after saving changes.
If the server is already running, use the existing preview.

## Version history

This repository tracks the active website. Other design variants, generated
copies, archives and local tool settings are excluded.

```sh
git status
git add site-live README.md .gitignore
git commit -m "Describe the website update"
```

## Online testing

Git stores version history; it does not host the website. Connect this
repository to an online Git repository and a static hosting service for a
shareable preview. The hosting publish directory must be `site-live`.
This website requires no build command.

No remote repository or online deployment has been configured yet.
