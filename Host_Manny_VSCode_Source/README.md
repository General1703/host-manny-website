# Host Manny Website — Editable VS Code Project

## File guide

- `index.html` — All the page content (title, headings, services, about, phone, links, sections).
- `style.css` — Design, colors, fonts, layout, mobile responsiveness.
- `Profile/Host Manny.jpg` — Host Manny profile picture used in the hero portrait.

There is **no JavaScript** in the supplied website.

## How to edit in Visual Studio Code

1. Extract the ZIP into its own folder.
2. Open **Visual Studio Code** and choose **File → Open Folder...**.
3. Select the extracted `Host_Manny_VSCode_Source` folder.
4. Open `index.html` to change website text and links.
5. Open `style.css` to change colors, spacing, fonts, mobile layout, etc.
6. To preview, open `index.html` in a web browser, or install/use VS Code **Live Server** and click **Go Live**.
7. Keep the `assets` folder alongside `index.html` and `style.css` so the image works.

## Notes

- `index.html` imports the CSS with `<link rel="stylesheet" href="style.css">`.
- To update the profile image, replace `Profile/Host Manny.jpg`.
- Editing these local files does not automatically publish changes to the live website.
- The original ZIP supplied to this chat had embedded CSS; this project separates and formats it for editing, keeping the same webpage content and style rules.
