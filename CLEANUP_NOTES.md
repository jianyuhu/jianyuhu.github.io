# Cleanup notes

- Removed demonstrably sample-only content: dummy CV, example blog posts, publications, talks, teaching and portfolio entries.
- Removed unused site pages and map generation scripts; preserved core Jekyll styling, includes, and assets.
- Rebuilt homepage and Research topics around the owner's documented research areas.
- Simplified top navigation to Home / Research / Publications / Talks / CV.
- Rebuilt CV and Talks pages from known, non-fabricated background information; confirm details before publication.
- Replaced wrong repository-prefixed PDF links with root-relative links.
- Fixed duplicate footer inclusion. Kept favicon, profile photos, common image assets, styles, JavaScript.
- Kept existing long-form stochastic publications, and added two key structure-preserving publications.
- Website has not been live-deployed. Build validity should be checked using GitHub Pages or `bundle exec jekyll build`.
