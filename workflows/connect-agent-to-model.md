# Connect an agent to a model

The general pattern is:

`Agent → provider configuration → API endpoint → runtime → model`

## Checklist

1. Install the agent.
2. Install or start the model runtime.
3. Test the model directly with the runtime.
4. Identify the runtime's API endpoint.
5. Add the endpoint and exact model identifier to the agent.
6. Configure authentication only when required.
7. Test a simple prompt.
8. Test tool calling separately.
9. Check logs for errors.

## Common failure points

- wrong base URL
- wrong model identifier
- API compatibility mismatch
- unsupported tool calling
- context window too small
- insufficient RAM/VRAM
- runtime not running
- authentication configured incorrectly

Do not assume that an OpenAI-compatible API supports every OpenAI feature. Test the exact features your agent needs.
