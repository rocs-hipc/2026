# ROCS HiPC 2026 Webpage

Single-page site for the **Reconfigurable Computing and Systems Workshop (ROCS 2026)**,
co-located with HiPC 2026, Bengaluru — **December 16, 2026**.

Content is derived from [`../cfp/CFP.md`](../cfp/CFP.md) and the accepted workshop
proposal in [`../proposal/`](../proposal/). Layout follows the
[2025 page](https://rocs-hipc.github.io/2025/).

## Publishing

The 2025 site lives in its own repo (`github.com/rocs-hipc/2025`) served by GitHub
Pages. Do the same for 2026:

The repo is <https://github.com/rocs-hipc/2026.git>, served by GitHub Pages:

```bash
cd 2026
git init -b main && git add . && git commit -m "ROCS 2026 workshop website"
git remote add origin https://github.com/rocs-hipc/2026.git
git push -u origin main
# then enable GitHub Pages (branch: main, folder: /) in repo settings
```

Target URL: <https://rocs-hipc.github.io/2026/>

## Still to fill in

Search `index.html` for `TBA` and `TODO`:

- Important dates — submission deadline, notification, camera-ready
- Linklings submission link (once HiPC opens the workshop track)
- Keynote / invited / industry speakers: names, titles, abstracts, bios
- Final program schedule — replace the TBA block with a table (see the 2025 page)
- Program committee members — replace the TBA block with the list
