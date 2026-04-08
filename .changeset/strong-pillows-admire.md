---
'@mastra/memory': patch
---

Fixed gateway model detection in Observational Memory processor to use duck typing instead of instanceof check, preventing potential failures from cross-package module resolution issues
