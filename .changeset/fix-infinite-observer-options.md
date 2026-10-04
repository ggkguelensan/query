---
'@tanstack/query-core': patch
---

Preserve infinite query options and the page parameter type when reading `InfiniteQueryObserver.options`, allowing the options to be passed back to `setOptions` without a type assertion.
