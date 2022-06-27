# pdf

Display pdf in VSCode.

**在原插件上改了一下，强行设置为暗黑模式，在VSCode中阅读pdf**

![screenshot](https://user-images.githubusercontent.com/38160059/175881799-0433221b-7333-4c37-90bf-6153c2de089a.png)

## Contribute

### Upgrade PDF.js

1. Download latest [Prebuilt](https://mozilla.github.io/pdf.js/getting_started/#download).
1. Extract the ZIP file.
1. Overwrite ./lib/* by extracted directories.
   - If lib/web/viewer.html has changes, apply these changes to HTML template at pdfPreview.ts.
1. To not use sample pdf.
  - Remove sample pdf called `compressed.tracemonkey-pldi-09.pdf`.
  - Remove code about using sample pdf from lib/web/viewer.js.
    ```js
    defaultUrl: {
      value: "", // "compressed.tracemonkey-pldi-09.pdf"
      kind: OptionKind.VIEWER
    },
    ```

## Change log
See [CHANGELOG.md](CHANGELOG.md).

## License
Please see [LICENSE](./LICENSE)
