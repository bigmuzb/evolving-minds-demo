# Evolving Minds Psychology Clinic Demo

Static one-page demo based on the public Evolving Minds Psychology Clinic website.

## Local preview

From this folder:

```powershell
python -m http.server 4177
```

Then open:

```text
http://localhost:4177/
```

## GitHub Pages

This can be hosted as a subfolder in a Pages repo, for example:

```text
https://username.github.io/demo-repo/evolving-minds-demo/
```

GitHub Pages serves one Pages site per repository, but that site can contain many demo folders.

## Published demo

Live URL:

```text
https://bigmuzb.github.io/evolving-minds-demo/
```

Final interaction settings:

- Cursor cloud is active only on fine pointer devices and disabled for reduced-motion users.
- Final asset versions are `styles.css?v=8` and `script.js?v=6`.
- The cursor effect is intentionally subtle, wider, and soft: `375px` radius, low alpha, `18px` blur.

Positioning note:

- The cursor cloud uses `z-index: 19`, below the sticky header at `z-index: 20`, so it remains visible across page content without covering the navigation.
