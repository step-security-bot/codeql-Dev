---
category: minorAnalysis
---
* Message events in the browser are now properly classified as client-side taint sources. Previously they were
  incorrectly classified as server-side taint sources, which resulted in some alerts being reported by
  the wrong query, such as server-side URL redirection instead of client-side URL redirection.
