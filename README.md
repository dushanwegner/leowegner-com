# leowegner.com

The site at **leowegner.com**. One HTML file, published by GitHub Pages.

## How to change the page

1. Edit `index.html`.
2. Commit and push to `main`.
3. Wait about a minute. That is the whole deployment.

There is no build step, no framework and nothing to install. The parts meant
to be edited are marked `EDIT ME` in the file.

## Why it is built this way

Because the job is a page, not an application. A static file on GitHub Pages
has no server to keep patched, no database to back up, no certificate to renew
and no monthly bill — and it cannot go down in a way anyone has to fix at
midnight. The previous site here was a Django application on a rented box; it
served a course that has ended.

`CNAME` is what tells GitHub Pages to answer for `leowegner.com`. **Do not
delete it** — without it the custom domain stops working and the site falls
back to the `github.io` address.

## History

This domain ran LeoUniversity until September 2026. That application and its
data are archived; the code remains at `github.com/leowegner/LeoUniversity`.
