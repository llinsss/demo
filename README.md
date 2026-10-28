# llins — Product builder

A portfolio shaped around public projects and experiments by [@llinsss](https://github.com/llinsss).

## Live sites

- [Portfolio](https://llinsss-portfolio.llinsomoudu.chatgpt.site) — scroll-driven work showcase.
- [Desktop portfolio](https://llins-desktop.llinsomoudu.chatgpt.site) — macOS-style lock screen, desktop, and app windows.

## Source

The original portfolio lives in [dist/index.html](dist/index.html). The separate desktop experience lives in [desktop/dist/index.html](desktop/dist/index.html), with its own Sites manifest in [desktop/.openai/hosting.json](desktop/.openai/hosting.json). Both are static HTML, CSS, and browser JavaScript with no package install or build step.

To preview the original portfolio:

```sh
python3 -m http.server 8000 -d dist
```

To preview the desktop portfolio:

```sh
python3 -m http.server 8000 -d desktop/dist
```
