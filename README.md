# trimtab-demo

The demo service for trimtab's stage 3 proof: a page listing transactions.
Production (`deploy/production.yaml`, on the trimtab kind cluster) serves the
default branch's `site/` and picks up each merge within a minute.
