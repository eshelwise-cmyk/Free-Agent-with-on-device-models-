# MCP skill

Model Context Protocol connects agents to external tools and data sources.

## Use MCP carefully

1. Identify exactly what the server can access.
2. Read its documentation and, when practical, source.
3. Give it only the permissions required for the task.
4. Avoid connecting unnecessary servers because their tool definitions consume model context.
5. Keep credentials scoped to the smallest useful permission set.
6. Test with non-sensitive data first.

MCP is a tool interface, not a security boundary by itself.
