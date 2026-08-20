# Instalação detalhada

Ministério Público SP: Inquérito Civil é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_mp_sp_inquerito_civil`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_mp_sp_inquerito_civil` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_mp_sp_inquerito_civil` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_mp_sp_inquerito_civil` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.mp_sp_inquerito_civil` (ou `servers.mp_sp_inquerito_civil` no VS Code) do config do cliente e reinicie.
