# GammaRemover

![GammaRemover — free open-source tools to remove the Made with Gamma watermark: web, CLI, MCP, agent skills, guides](assets/banner.webp)

Free, open-source tools for [Gamma.app](https://gamma.app) users — remove the "Made with Gamma" watermark from PDF and PPTX exports, in the browser, on the command line, or through AI agents.

**[gammaremover.com](https://gammaremover.com)** — the web app. Runs 100% in your browser via WebAssembly: no upload, no signup, no file limits. Available in 14 languages.

## Projects

| Repository | What it is |
|------------|------------|
| [gamma-watermark-remover](https://github.com/gammaremover/gamma-watermark-remover) | CLI + Python library. `pip install gamma-watermark-remover` |
| [gamma-watermark-remover-mcp](https://github.com/gammaremover/gamma-watermark-remover-mcp) | MCP server for Claude Desktop, Claude Code, and any MCP client |
| [gamma-watermark-remover-skill](https://github.com/gammaremover/gamma-watermark-remover-skill) | Agent skill for Claude Code and OpenClaw |
| [gamma-watermark-remover-webui](https://github.com/gammaremover/gamma-watermark-remover-webui) | Local drag-and-drop web UI — files stay on your machine |
| [gamma-export-guide](https://github.com/gammaremover/gamma-export-guide) | Guide to exporting Gamma presentations without the watermark |
| [awesome-gamma](https://github.com/gammaremover/awesome-gamma) | Curated tools, guides, and resources for Gamma users |

## How it works

The "Made with Gamma" badge in an exported file is a discrete document object — an image with a gamma.app hyperlink in PDFs, a hyperlinked shape on the slide master in PPTX files. Every tool here deletes that object structurally: no re-rendering, no quality loss, text stays selectable, slides stay editable. Detection logic is [fully documented](https://github.com/gammaremover/gamma-watermark-remover#how-detection-works).

For files you created and have the right to modify. Not affiliated with Gamma.app.
