Do I need to understand transpilers?
sorta: should understand difference between bundling and transpiling, and why
having heard of Rollup and Babel helps too

How to do code splitting?
manually 'cause that's the way we like it
having said that, perhaps Rollup? contributions welcome

Why Rollup?
readable, straightforward source, tree shaking, comparatively easy to grok the concepts

Why constraints
separation of concerns: build system should not influence source and vice versa
replaceability

Why no minification?
View Source
GZIP good enough
bundles should be small anyway

Why no Sass globbing?

code splitting?
maybe Rollup; contributions welcome

serving native ESNext
⇒ two similar bundles - second one optional via ENV
