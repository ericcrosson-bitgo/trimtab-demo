# trimtab-demo

A static page listing transactions from `site/transactions.json`.

- Run it: `python3 -m http.server 8080 --directory site`, then open
  `http://127.0.0.1:8080/`.
- There is no build step and no test suite. Keep it dependency-free: plain
  HTML and JavaScript in `site/`.
- Production serves the default branch: every merge is live within a minute.
