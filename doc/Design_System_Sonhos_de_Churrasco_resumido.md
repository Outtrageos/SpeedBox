# Design System --- Sonhos de Churrasco

## 1. Conceito visual

Identidade moderna, elegante e organizada, inspirada no calor da brasa e
no churrasco, sem excesso de elementos temáticos. Manter consistência em
todas as páginas.

## 2. Paleta de cores

  Cor               HEX         Uso
  ----------------- ----------- ----------------------------------------------
  Amarelo           `#FFC928`   Cor primária, destaques e chamadas para ação
  Laranja           `#F47721`   Cor secundária, botões e detalhes
  Vermelho escuro   `#861F18`   Ênfase e destaques especiais
  Preto             `#171717`   Títulos, textos e fundos escuros
  Cinza             `#777777`   Textos auxiliares e divisórias
  Cinza claro       `#F5F5F5`   Fundos neutros

Cores auxiliares: branco `#FFFFFF`, bordas `#E2E2E2` e texto sobre
fundos escuros `#FFFFFF`. Usar amarelo e laranja com equilíbrio e
verificar o contraste para garantir legibilidade.

## 3. Tipografia

-   **Títulos:** Super Chips.
-   **Textos, menus e botões:** Quicksand Bold.
-   Usar Super Chips preferencialmente em títulos curtos; evitar textos
    longos em maiúsculas.
-   Altura de linha para textos corridos: `1.4–1.6`.

  Elemento           Desktop   Mobile
  ---------------- --------- --------
  H1                   48 px    34 px
  H2                   36 px    28 px
  H3                   28 px    23 px
  H4                   22 px    19 px
  Parágrafo            16 px    15 px
  Texto auxiliar       14 px    13 px
  Botão                16 px    15 px
  Legenda              12 px    12 px

## 4. Botões

Todos devem ter textos objetivos, boa área de toque e cantos
arredondados.

-   **Primário --- Fazer pedido:** fundo amarelo `#FFC928`, texto preto
    `#171717`, altura `48px`, raio `8px`, padding horizontal `24px`, sem
    borda.
-   **Secundário --- Ver cardápio:** fundo laranja `#F47721`, texto
    preto `#171717`, altura `48px`, raio `8px`.
-   **Alternativo --- Saiba mais:** estilo preto.

Estados: normal (cor original), hover (escurecimento leve), active
(pequena redução visual), focus (contorno visível), disabled (opacidade
reduzida e sem interação) e loading (indicador de carregamento).

## 5. Formulários

Campos padrão: nome completo, e-mail e mensagem, com botão **Enviar**.

  Propriedade   Padrão
  ------------- ---------------
  Altura        48 px
  Raio          8 px
  Borda         `#E2E2E2`
  Fundo         `#FFFFFF`
  Texto         `#171717`
  Placeholder   `#777777`
  Foco          Borda amarela
  Erro          `#861F18`

Manter rótulos visíveis, identificar campos obrigatórios, exibir erros
próximos aos campos e adaptar os formulários para dispositivos móveis.

## 6. Cards e componentes

Tipos de cards: - **Produto:** imagem, nome, descrição, preço e ação
"Pedir agora". - **Evento:** imagem, nome, data, horário, descrição e
ação "Ver evento". - **Avaliação:** nome do cliente, nota, comentário e
indicação de publicação.

Componentes reutilizáveis: Header, Footer, Hero Section, Product Card,
Event Card, Review Card, CTA Button/Banner, Contact Section, Delivery
Information, Breadcrumb, Modal, Form Input, Badge, Pagination, Admin
Sidebar/Header, Data Table e Confirmation Modal.

## 7. Bordas, sombras e espaçamento

  Elemento                                Padrão
  --------------------------------------- ---------------------
  Bordas de cards, campos e separadores   `1px solid #E2E2E2`
  Botões                                  Sem borda
  Raio de botões e campos                 8 px
  Raio de cards                           12 px
  Raio de imagens                         10 px
  Raio de modais                          16 px

Sombras discretas: - Pequena: `0 2px 6px rgba(0,0,0,0.08)`. - Média:
`0 4px 12px rgba(0,0,0,0.12)`. - Elevada: `0 8px 24px rgba(0,0,0,0.14)`.

Escala de espaçamento baseada em múltiplos de 4 px: `XS 4`, `SM 8`,
`MD 16`, `LG 24`, `XL 32`, `2XL 48`, `3XL 64` e `4XL 80`.

## 8. Responsividade

  Dispositivo               Largura Comportamento
  --------------- ----------------- -----------------------------
  Smartphone             Até 767 px Uma coluna e menu recolhido
  Tablet               768--1023 px Até duas colunas
  Desktop             1024--1439 px Layout completo
  Desktop amplo     1440 px ou mais Conteúdo centralizado

-   **Smartphones:** menu hambúrguer, cards em uma coluna ou grade
    compacta, botões com pelo menos 44 px de altura, imagens adaptáveis
    e formulários em coluna única.
-   **Tablets:** menu adaptado, grades de duas colunas e espaçamentos
    intermediários.
-   **Desktops:** menu horizontal, grades de três ou quatro colunas e
    banner com texto e imagem lado a lado.

## 9. Tokens e implementação

  Token                 Valor
  --------------------- -------------
  `--color-primary`     `#FFC928`
  `--color-secondary`   `#F47721`
  `--color-accent`      `#861F18`
  `--color-dark`        `#171717`
  `--color-gray`        `#777777`
  `--color-light`       `#F5F5F5`
  `--font-heading`      Super Chips
  `--font-body`         Quicksand
  `--radius-button`     8px
  `--radius-card`       12px
  `--spacing-section`   64px
  `--container-width`   1200px

Organização sugerida: - `components/layout`: cabeçalho, rodapé e
navegação. - `components/buttons`: botões e links de ação. -
`components/cards`: produtos, eventos e avaliações. -
`components/forms`: campos, formulários e validações. -
`components/sections`: banners e seções reutilizáveis. -
`components/admin`: menus, tabelas e componentes administrativos. -
`styles`: variáveis, tipografia, espaçamentos e estilos globais.

No Tailwind CSS, criar tokens equivalentes para cores, fontes,
espaçamentos e bordas. Disponibilizar as fontes oficiais antes da
implementação e não substituir Super Chips sem autorização.

## 10. Princípios finais

1.  **Consistência:** componentes com aparência e comportamento
    padronizados.
2.  **Simplicidade:** informações e funções fáceis de encontrar.
3.  **Identidade:** preservar amarelo, laranja e referências à brasa.
4.  **Responsividade:** experiência adequada em computadores e
    celulares.
5.  **Manutenção:** centralizar componentes e tokens.

**Observação:** os códigos HEX são sugestões digitais para representar
as cores descritas. Conferir com os arquivos oficiais da identidade
visual e testar o contraste antes da implementação definitiva.
