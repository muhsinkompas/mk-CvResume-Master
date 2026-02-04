# Fonts Folder

Place your custom `.ttf` or `.otf` font files here.

## Recommended Free Fonts

- [Roboto](https://fonts.google.com/specimen/Roboto) - Modern, clean
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+3) - Professional
- [Lato](https://fonts.google.com/specimen/Lato) - Friendly, readable
- [Open Sans](https://fonts.google.com/specimen/Open+Sans) - Versatile

## File Naming Convention

For the template to work correctly, name your font files like this:

```
FontName-Regular.ttf
FontName-Bold.ttf
FontName-Italic.ttf
FontName-BoldItalic.ttf
```

## Example

```
fonts/
├── Roboto-Regular.ttf
├── Roboto-Bold.ttf
├── Roboto-Italic.ttf
└── Roboto-BoldItalic.ttf
```

Then update `resume.tex`:

```latex
\setmainfont{Roboto}[
    Path = ./fonts/,
    Extension = .ttf,
    UprightFont = *-Regular,
    BoldFont = *-Bold,
    ItalicFont = *-Italic,
    BoldItalicFont = *-BoldItalic
]
```
