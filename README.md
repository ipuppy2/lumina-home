# Lumina Markdown

Lumina Markdown is a focused Markdown reader for macOS.

This repository contains the public static homepage for Lumina Markdown. The site introduces the app, its free and licensed features, and links users to the latest macOS release.

## What Is Lumina Markdown?

Lumina Markdown is built for reading and managing local Markdown documents on macOS. It keeps the reading experience clean while supporting technical writing workflows such as outlines, formulas, diagrams, PDF export, long image export, and local knowledge-base navigation.

## Highlights

- Native macOS reading experience
- Markdown outline and multi-document tabs
- Math, diagrams, code blocks, and technical documents
- Cross-document search for local document libraries
- Live folder refresh when Markdown files change
- PDF export and full-page image export
- Auto-scroll reading mode
- Account-based feature authorization

## Website

The homepage is a plain static site and can be hosted directly on GitHub Pages.

Main entry:

```text
index.html
```

The download buttons request a download URL from the backend. Before publishing, replace the `lumina-download-api` meta tag in `index.html` with the public HTTPS backend origin.

下载地址由 backend 的 `/download-url` 接口动态返回，页面不再公开写死发布地址。

## Local Preview

```bash
python3 -m http.server 4174 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4174/
```

## License

See [LICENSE](LICENSE).
