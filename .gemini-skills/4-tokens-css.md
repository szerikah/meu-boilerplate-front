---
name: tokens
description: Lê um frame de Design System no Figma e extrai as cores e tipografia para variáveis CSS.
---

# Instruções da Skill
Ao receber um link do Figma contendo um guia de estilos ou um componente:
1. Use o Figma MCP para ler as propriedades visuais.
2. Extraia todas as cores únicas e tamanhos de fonte.
3. Gere um bloco de código CSS contendo apenas as variáveis na raiz (dentro de `:root { }`).
4. Nomeie as variáveis de forma semântica (ex: `--cor-primaria`, `--fonte-titulo-xl`).