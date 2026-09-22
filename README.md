# Harness Design Notes

Static site, no build step. Every page is self-contained HTML.

- `/` landing
- `/jev-economics/` What Jev's Price Card Implies
- `/speculation-ceiling/` The Speculation Ceiling — Speculative tool calling, part 1
- `/speculative-decoding/` Speculative Decoding
- `/does-speculation-pay/` Does Speculation Pay? — Speculative tool calling, part 2
- `/assets/` icons and Open Graph cards

Bump the `?v=` query on the favicon links in each page's head to force browsers to refetch icons.
