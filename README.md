# NorthForkTech

Static landing page for [northforktech.org](https://northforktech.org).

## Local preview

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000.

## Deploy to Cloudflare Pages

Connect the GitHub repository to Cloudflare Pages. Choose no framework, leave the build command empty, and use `/` as the output directory. Add `northforktech.org` as a custom domain.

## Before publishing

The **Request an invite** buttons currently use `hello@northforktech.org` as a **placeholder**. Set up that email address or change the `mailto:` links to a working contact method. Do not publish the placeholder as-is unless email forwarding is configured.
