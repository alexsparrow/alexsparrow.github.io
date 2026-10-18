# alexsparrow.github.io

GitHub Pages user site for `alexsparrow`. It does two things, so keep it unarchived:

1. **Redirects to [alexsparrow.org](https://alexsparrow.org).** `index.html` is a redirect that runs as soon as `https://alexsparrow.github.io/` loads.
2. **Hosts project Pages sites.** Any repo with Pages turned on is served under this site at `https://alexsparrow.github.io/<repo>/`, for example [Sigurd](https://alexsparrow.github.io/sigurd/).

There's deliberately no custom domain (`CNAME`). This site used to serve `www.alexsparrow.me`, but that domain now redirects to alexsparrow.org through Cloudflare, configured in the private `alexsparrow/alexsparrow` monorepo. Adding a `CNAME` here would also move every project site onto that domain.

Everything else I publish lives in that monorepo.
