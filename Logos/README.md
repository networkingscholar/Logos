# Networking Scholar Logo Library

This folder is the central logo source for the Networking Scholar website and learning platform.
The platform reads it from the `NKS-Logos` branch of `networkingscholar/Logos` and shows every
supported image here in its **Logo Library** (Admin > Website > Logo Library, and the
"Browse Logo Library" button next to each logo setting).

Add a logo by committing it into the right subfolder. Then press **Refresh** in the Logo Library.
Nothing on the website changes until an admin (or an instructor, where allowed) selects the logo and saves.

| Folder | What goes in it |
|---|---|
| `Brand/` | Primary company and application logos in full colour. |
| `Light/` | Variants made for light backgrounds (dark or black artwork). |
| `Dark/` | Variants made for dark backgrounds (white or light artwork). |
| `Watermarks/` | Logos meant for watermarks on notes and documents (simple shapes, transparent background). Opacity and position are set in the app, so keep the file itself fully opaque. |
| `Courses/` | Course and training logos (CCNA, CCNP, Firewall and so on). |
| `Icons/` | Square icons, favicons and small graphics. |

Subfolders inside these folders are fine (for example `Courses/Cisco/ccna.png`); the library lists them too.

## Supported formats

- **PNG** (`.png`), best for logos. Use a transparent background where possible.
- **SVG** (`.svg`), sharp at every size on web pages. PDF certificates need PNG, JPEG or WebP.
- **JPEG** (`.jpg`, `.jpeg`), fine for photos and logos on a solid background.
- **WebP** (`.webp`).

Other files (README, ZIP, and so on) are ignored by the library. Keep each file under 4 MB.

## Naming

Use lowercase words joined by hyphens, and say what the variant is, for example
`networking-scholar-logo-white-on-transparent.png`. Renaming or deleting a file that is already in use
does not break the website: the platform keeps a saved copy and shows a warning so an admin can pick a replacement.

## Files at the top of the branch

The original logo files at the top of this branch are kept as they were. The files in these folders are copies,
sorted by use.
