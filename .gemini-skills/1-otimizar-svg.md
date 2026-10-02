---
name: svg
description: Converte vetores do Figma via MCP, limpa tags desnecessárias e aplica currentColor.
---

# Instruções da Skill
Quando esta skill for acionada e receber um link de um nó do Figma, execute estritamente o seguinte fluxo:
1. Use a conexão Figma MCP para ler a geometria e as propriedades do nó fornecido.
2. Converta esses dados em uma tag `<svg>` semântica e limpa.
3. Remova quaisquer tags `<defs>` ou metadados inúteis.
4. Substitua atributos fixos de cor por `currentColor`, garantindo que o ícone possa ser estilizado via CSS.
5. Certifique-se de que o `viewBox` está correto para facilitar a responsividade no front-end.
6. Retorne apenas o código final estruturado, sem explicações extras.