# Harness Design Notes

Static site, no build step. Every page is self-contained HTML.

- `/` landing
- `/speculation-ceiling/` The Speculation Ceiling
- `/speculative-decoding/` Speculative Decoding
- `/does-speculation-pay/` Does Speculation Pay?
- `/assets/` icons and Open Graph cards

Bump the `?v=` query on the favicon links in each page's head to force browsers to refetch icons.
