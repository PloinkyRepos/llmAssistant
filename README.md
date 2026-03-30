# llmAssistant

Repository for lightweight LLM utilities shared by other agents and UIs.

## Components

- [llmAssistant](./llmAssistant/README.md): MCP agent for autocomplete, commit message generation, and conflict resolution

## Integration notes

- the runtime is provider-agnostic and uses the default LLM agent from `achillesAgentLib`
- credentials are expected through env or `.ploinky/.secrets`
