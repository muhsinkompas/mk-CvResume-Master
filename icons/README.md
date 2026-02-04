# Icons Folder

Place your SVG icon files here for use in the header.

## Required Icons

The template expects these icon files for the header with photo:

- `iphone.svg` - Phone icon
- `envelope.svg` - Email icon
- `linkedin.svg` - LinkedIn icon
- `github.svg` - GitHub icon
- `website.svg` - Website/globe icon

## Where to Get Icons

You can download free SVG icons from:

- [Font Awesome](https://fontawesome.com/icons) - Large icon library
- [Feather Icons](https://feathericons.com/) - Clean, minimal icons
- [Simple Icons](https://simpleicons.org/) - Brand icons (GitHub, LinkedIn, etc.)
- [Heroicons](https://heroicons.com/) - Beautiful hand-crafted SVG icons
- [Lucide](https://lucide.dev/) - Open source icons

## Usage in LaTeX

```latex
\includesvg[height=1.0em]{iconname}  % without .svg extension
```

## Note

SVG support in LaTeX requires Inkscape to be installed on your system.

If you don't want to use SVG icons, you can modify the `\makeheaderwithphoto` command in `resume.tex` to use text-based separators instead.
