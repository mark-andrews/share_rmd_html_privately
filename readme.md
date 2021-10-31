A demo of how to password protect a html page used in GitHub pages.

A html file, rendered from a RMarkdown file, is place in `docs/` and then GitHub pages is activated.

The html file is encrypted using [`staticrypt`](https://github.com/robinmoisson/staticrypt), e.g.
```
staticrypt demo.html '7;b4kJB{' -o demo2.html
```

Now, the `demo2.html` is put in `docs` and so available through GitHub pages, but it requires the password to view.
