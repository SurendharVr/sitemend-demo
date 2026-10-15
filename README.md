# sitemend-demo

A tiny static site guarded by the [sitemend](https://github.com/SurendharVr/sitemend) GitHub Action ([workflow](.github/workflows/sitemend.yml)).
The [open pull request](https://github.com/SurendharVr/sitemend-demo/pull/2) leaks a `*.vercel.app` preview host into the sitemap and `og:url` and drops a canonical, so sitemend fails the check and comments with the evidence.
