# Hadith Data Repository

This repository contains hadith book data for the [Hadith Hub](https://hadithhub12.github.io/hadith-hub/) app.

## Contents

- **625** Arabic books
- **0** English translations
- **Total size**: 543.91 MB

## Structure

```
hadith-data/
├── books.json          # Manifest of all books
├── books/              # Arabic book files
│   ├── slug-v001.zip
│   ├── slug-v002.zip
│   └── ...
└── translations/       # English translations
    └── ...
```

## Usage

The manifest (`books.json`) contains URLs for all book files. The app fetches this manifest and downloads individual volumes on demand.

## License

The hadith texts are from public Islamic sources. This repository is for educational purposes.
