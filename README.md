# Colorarium: Guia Visual de Cores

Catálogo interativo com 500 cores organizadas por família cromática e por tema. Cada cor tem códigos, significado, sugestões de uso, combinações, tons vizinhos, cor complementar e uma paleta sugerida.

**Demonstração:** [liviavittoria28-create.github.io/COR](https://liviavittoria28-create.github.io/COR/) · **Autora:** [Lívia Vittoria](https://github.com/liviavittoria28-create)

![Busca por "azul" no Colorarium](docs/screenshot.jpg)

---

## Objetivo

Oferecer uma referência rápida para escolher cores com critério, sem precisar alternar entre várias ferramentas.

## Problema que resolve

Seletores de cor mostram o código HEX, mas não ajudam a decidir: que sensação a cor transmite, com o que combina, onde usar. O Colorarium junta essas informações numa ficha por cor e permite navegar por famílias (vermelhos, azuis, terrosos…) e por temas (oceano, botânico, retrô, inverno suave…).

## Funcionalidades

- Busca por nome da cor ou código HEX.
- Filtros por família cromática e por tema (mais de 50 categorias).
- Ficha de cada cor: códigos, significado, onde usar, combinações, tons da mesma família, cor complementar e paleta sugerida.
- Cópia do código HEX para a área de transferência.
- Layout responsivo.

## Tecnologias

HTML5, CSS3 e JavaScript puros, num único arquivo. A interface é gerada a partir de um conjunto de dados de cores no próprio script. Tipografia com Cormorant Garamond e DM Sans (Google Fonts).

## Estrutura de pastas

```
index.html        página, estilos, dados das cores e lógica de busca e filtros
docs/
  screenshot.jpg  captura usada neste README
```

## Como executar

Abra `index.html` no navegador. Não há dependências, variáveis de ambiente nem banco de dados.

## Testes

Não há testes automatizados. Verificação manual feita em 17/11/2026 no Chrome: a página carrega sem erros de JavaScript, a busca por "azul" filtra os resultados e o GitHub Pages está publicado.

## Limitações conhecidas

- Os dados das cores ficam dentro do HTML, o que deixa o arquivo grande e difícil de editar.
- Ainda não é possível exportar uma paleta.

## Melhorias futuras

- Mover os dados para um arquivo JSON separado.
- Exportar paletas (CSS, PNG).
- Verificar contraste entre pares de cores (WCAG).

---

Desenvolvido por **Lívia Vittoria** · [Portfólio](https://liviavittoria28-create.github.io) · [LinkedIn](https://www.linkedin.com/in/livia-vittoria-732b8a430/)
