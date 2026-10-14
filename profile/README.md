# BrowseCraft

We're building **[Browsecraft](https://github.com/browsecraft-dev/browsecraft)**, a small web browser written in Rust with its own rendering engine. It doesn't use a WebView or a system web engine. Browsecraft parses HTML and CSS, runs the cascade, lays out the page and paints it in software.

```
URL ─► net ─► html ─► DOM ─► css + style ─► layout ─► display list ─► paint ─► window
```

## Get involved

- Browse the [open issues](https://github.com/browsecraft-dev/browsecraft/issues), especially ones labelled `good first issue`
- Read the [contributing guide](https://github.com/browsecraft-dev/browsecraft/blob/main/CONTRIBUTING.md)
- Every change goes through a pull request and gets one review before it merges
