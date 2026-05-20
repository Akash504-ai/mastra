---
'@mastra/core': minor
'@mastra/workflows-inngest': minor
'@mastra/workflows-temporal': minor
---

Add transparent workflow runner adapters for Inngest and Temporal workflows.

This introduces a generic WorkflowRunner abstraction and allows standard Mastra workflows to execute on external workflow engines without requiring workflow rewrites.

Included:
- runner support in createWorkflow()
- InngestRunner adapter
- TemporalRunner adapter
- runner integration tests
- backward-compatible workflow behavior