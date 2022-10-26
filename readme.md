# Instagram Web Archiving

A small, but hopefully growing, demo of archiving CCA-related Instagram feeds using the WebRecorder tool suite.

Use the "autopilot" feature to record on Instagram: https://archiveweb.page/en/features/autopilot/

Embed result here but also playable in the Chrome extension.

https://replayweb.page/docs/embedding

See note about embed being too small; need to add CSS to make replayer's container 100% size so stuff inside the replaying is visible.

Python SimpleHTTPServer doesn't support "range" requests so the replayer doesn't work with it, but we can use node's [http-server](https://www.npmjs.com/package/http-server) which can be run like `npx http-server .` and runs on http://localhost:8080 — there's a `npm run server` command for this.

## Accounts to archive

https://www.instagram.com/emeryville_mudflats/
https://www.instagram.com/cca.oakland.legacy/

## Large WACZ files & git LFS

When you upload a file >50mb to GitHub, it warns you about their large files policy, and >100mb is not allowed at all. This repo uses [git lfs](https://git-lfs.github.com/) to track its large files and store them on GitHub. To set up lfs, you should just need to install it on your system (e.g. `brew install git-lfs`), it is configured for this repo in the .gitattributes file. From reading GitHub's [large file storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github) documentation, it sounds like we can store files [up to 2GB in size](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage).

## LICENSE

[ECL Version 2.0](https://opensource.org/licenses/ECL-2.0)
