# Instagram Web Archiving

Using the WebRecorder tool suite.

Use the "autopilot" feature to record on Instagram: https://archiveweb.page/en/features/autopilot/

Embed result here but also playable in the Chrome extension.

https://replayweb.page/docs/embedding

See note about embed being too small; need to add CSS to make replayer's container 100% size so stuff inside the replaying is visible.

The Python SimpleHTTPServer doesn't support "range" requests so the replayer won't work with them, but you can use node's [http-server](https://www.npmjs.com/package/http-server) which can be run like `npx http-server .` and runs on http://localhost:8080 — there's a `npm run server` command for this.

## Accounts to archive

https://www.instagram.com/emeryville_mudflats/
https://www.instagram.com/cca.oakland.legacy/

## LICENSE

[ECL Version 2.0](https://opensource.org/licenses/ECL-2.0)
