# tipografia_itau
# Guia de Estilo: Tipografia e Cores

Este repositório contém as diretrizes do **Guia de Tipografia e Cores**, estabelecendo padrões visuais, escala tipográfica, regras de hierarquia e acessibilidade por contraste para o projeto/marca.

---

## 📌 Visão Geral

O objetivo deste guia é padronizar a identidade visual e os componentes de interface (UI), garantindo consistência, hierarquia clara e leitura confortável em todas as plataformas digitais.

---

## ✒️ Tipografia

A família tipográfica oficial do projeto é a **Poppins**, uma fonte sans-serif geométrica, moderna e legível.

### Escala Tipográfica (Font Scale)

Para manter a consistência e a proporção hierárquica em toda a aplicação, utilize a escala definida abaixo:

| Nível / Elemento | Tamanho (px) | Aplicação Sugerida |
| :--- | :---: | :--- |
| **H1** | `40px` | Títulos principais de páginas / Cabeçalhos de topo |
| **H2** | `34px` | Títulos de seções primárias |
| **H3** | `28px` | Subtítulos e títulos de blocos de conteúdo |
| **H4** | `24px` | Títulos de cartões (cards) ou componentes maiores |
| **H5** | `18px` | Subseções, destaques e títulos menores |
| **Parágrafo** | `16px` | Texto de corpo padrão (Body text) |
| **Small** | `14px` | Legendas, rótulos de formulário, notas e metadados |

---

## 🎨 Cores & Contraste

O guia prevê validação de contraste e aplicação da marca:
- **Identidade Visual:** Aplicação da marca institucional (Itaú).
- **Acessibilidade:** Aplicação da escala tipográfica sobre fundos com níveis adequados de contraste (atendendo às diretrizes de acessibilidade WCAG).

---

## 💻 Exemplo de Implementação (CSS)

```css
:root {
  /* Família Tipográfica */
  --font-family-base: 'Poppins', sans-serif;

  /* Escala de Fontes */
  --font-size-small: 14px;
  --font-size-body: 16px;
  --font-size-h5: 18px;
  --font-size-h4: 24px;
  --font-size-h3: 28px;
  --font-size-h2: 34px;
  --font-size-h1: 40px;
}

body {
  font-family: var(--font-family-base);
  font-size: var(--font-size-body);
  line-height: 1.5;
}

h1 { font-size: var(--font-size-h1); }
h2 { font-size: var(--font-size-h2); }
h3 { font-size: var(--font-size-h3); }
h4 { font-size: var(--font-size-h4); }
h5 { font-size: var(--font-size-h5); }
small { font-size: var(--font-size-small); }
