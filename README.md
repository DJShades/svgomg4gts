# SVGOMG! for GTS

[SVGOMGの本家](https://github.com/jakearchibald/svgomg) の 2019/9/30 のコミットより、precision 0 だとGTSでSVGが崩れてしまうことがあるため、一時的に前のバージョンを公開するためにフォークしました。

# Running locally

Install dependencies:

```sh
npm install
```

Run dev server:

```sh
npm run serve
```

Or, run without the offline capabilities:

```sh
npm run serve-no-sw
```

Running without offline capabilities means you get the latest version each time you hit refresh. The dist offline-first mobile serves the cached version first then checks for updates in the background.
