# Activity Images

These images appear in the **Extracurricular Activities** gallery on the
portfolio website (`index.html` → `robotics-gallery`).

## How to update an image on the website

The website links to each image by its **filename**. To swap a photo, just
replace the file here with a new one **using the exact same filename**, then
commit and push. No HTML changes are needed — the live site updates
automatically once the change reaches the `main` branch.

| Filename            | Where it shows / what it should be                          |
| ------------------- | ---------------------------------------------------------- |
| `rambot.jpg`        | RAMbot — the WSU RAM Robotics Club robot                    |
| `robocup-ssl-1.jpg` | RoboCup SSL soccer robots on the field                     |
| `robocup-ssl-2.jpg` | RoboCup SSL competition field (wider shot)                 |
| `turtle-rabbit.jpg` | Turtle Rabbit 2025 RoboCup SSL team logo                   |

### Steps

1. Save your new photo with the **same name** as the one you want to replace
   (e.g. name it `rambot.jpg` to replace the RAMbot photo).
2. Drop it into this `images/activities/` folder, overwriting the old file.
3. Commit and push to GitHub. If you use a `.jpg` file with the same name,
   that's all — the website picks it up automatically.

### Notes

- Keep the same file extension (`.jpg`). If you must use a different format
  (e.g. `.png`), you'll also need to update the matching `src` in
  `index.html`.
- Recommended size: roughly 320×240 or larger, landscape orientation, so all
  four images line up evenly in the gallery.
- To **add** a new gallery image (rather than replace one), drop the file here
  and add a matching `<img src="images/activities/your-file.jpg" ...>` line to
  the `robotics-gallery` section in `index.html`.
