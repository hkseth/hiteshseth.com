# hiteshseth.com

Personal landing page for [hiteshseth.com](https://hiteshseth.com).

A single self-contained `index.html` — no framework, no build step. Inline CSS,
light/dark mode via `prefers-color-scheme`, responsive.

`me.vcf` is the contact card served at <https://hiteshseth.com/me.vcf>. It is
deliberately unlinked from the page — the URL exists to be handed out directly, or
encoded into a QR code. It's a vCard 3.0 file with `portrait.jpg` embedded
as a base64 `PHOTO`, so it stays a single hand-editable file with no fetch at import
time — just keep lines folded at 75 octets and the line endings CRLF.

## Preview locally

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
