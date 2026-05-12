# Foundation Machines branding

Source assets and exports for the Foundation Machines visual identity.

## Mark

The mark is a stylised "M" formed by two opposing right triangles that meet along a diagonal split. It reads as a chevron and as the letter M, and it is meant to feel like a stamp or foundry mark.

| File                     | Use                                                     |
| ------------------------ | ------------------------------------------------------- |
| `avatar-light.svg`       | Vector source. Cream mark on dark chip. Default.        |
| `avatar-dark.svg`        | Vector source. Dark mark on cream chip. For light surfaces. |
| `avatar-500.png`         | 500x500 PNG export. GitHub org / social avatars.        |
| `avatar-1024.png`        | 1024x1024 PNG export. Higher-resolution surfaces.       |
| `social-preview.svg`     | Vector source for the GitHub social preview.            |
| `social-preview-1280x640.png` | 1280x640 PNG export. GitHub repo "Social preview" image. |

## Palette

| Token       | Hex      | Use                          |
| ----------- | -------- | ---------------------------- |
| Ink         | `#1a1612` | Primary dark surface, mark on light backgrounds. |
| Bone        | `#f5efe3` | Primary light surface, mark on dark backgrounds. |
| Stone       | `#a39689` | Secondary text on dark surfaces. |

## Typography

Wordmark uses the system UI sans stack (`-apple-system`, `BlinkMacSystemFont`, Inter, Helvetica Neue) at semibold (600) weight with `-2` letter-spacing.

## Regenerating PNGs

PNGs are exported from the SVG sources with `rsvg-convert`:

```
rsvg-convert -w 500  -h 500  branding/avatar-light.svg   -o branding/avatar-500.png
rsvg-convert -w 1024 -h 1024 branding/avatar-light.svg   -o branding/avatar-1024.png
rsvg-convert -w 1280 -h 640  branding/social-preview.svg -o branding/social-preview-1280x640.png
```

## Usage

These assets are published as part of the Foundation Machines organisation profile. They identify the Foundation Machines brand and may not be used to imply endorsement, partnership, or affiliation without permission. For brand or partnership questions, contact hello@foundationmachines.com.
