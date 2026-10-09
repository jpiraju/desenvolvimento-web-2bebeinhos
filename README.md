# 🚀 2bebeinhos

Loja virtual fictícia de presentes e produtos para bebês, desenvolvida como projeto evolutivo para estudo de Desenvolvimento Web.

> Presentes para celebrar os pequenos grandes momentos.

A identidade visual do projeto utiliza o conceito de dois bebês e uma temática espacial, que será desenvolvida gradualmente nas próximas etapas.

## Objetivo acadêmico

O objetivo é desenvolver progressivamente uma loja virtual enquanto são estudados conceitos de desenvolvimento web. O projeto será construído em etapas, permitindo acompanhar sua evolução desde uma página HTML básica até versões com estilização, responsividade e programação.

## 📌 Versão atual — 2.0

A versão 2.0 utiliza HTML5 semântico para organizar melhor a estrutura da página e demonstrar o uso das tags mais relevantes da linguagem, mantendo a identidade acadêmica do projeto.

Objetivos desta etapa:

- praticar a estrutura semântica do HTML5;
- utilizar corretamente `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`;
- organizar navegação, categorias e passos em listas HTML (`ul` e `ol`);
- promover hierarquia clara de títulos;
- apresentar tabela de catálogo e tabela comparativa de especificações;
- preparar integração de vídeo HTML5 com formatos MP4 e WebM.

**Tecnologia utilizada:**
- HTML5

**CSS e JavaScript continuam como tecnologias futuras.**

## Funcionalidades simuladas

A versão 2.0 mantém:

- identificação da loja;
- navegação interna por seções;
- vitrine de produtos com quatro itens;
- destaque do Kit Presente Recém-Nascido;
- simulação de carrinho através de âncoras HTML;
- informações e atendimento fictícios no rodapé;
- organização semântica e acessível do conteúdo.

O carrinho continua sem lógica real. Ele serve apenas para simular a navegação entre partes da página utilizando HTML.

## Estrutura semântica HTML5 aplicada

- `header`: identidade da loja, mensagem principal e navegação.
- `nav > ul > li > a`: navegação interna principal e links de atendimento no rodapé.
- `main`: conteúdo central da página.
- `section`: agrupamento temático (produtos, destaque, tabelas e carrinho).
- `article`: cada produto da vitrine e o produto em destaque.
- `aside`: conteúdo complementar com dica, categorias e passos de escolha.
- `footer`: políticas, atendimento e aviso acadêmico.

## Categorias e listas

No conteúdo complementar (`aside`) foram incluídas:

- lista não ordenada (`ul`) com categorias:
  - Kits de presente;
  - Roupinhas;
  - Mantas e acessórios;
  - Higiene e cuidados.
- lista ordenada (`ol`) com 3 passos para escolher um presente.

## Tabelas da versão 2.0

- **Tabela de catálogo**: mantém o resumo dos quatro produtos com categoria e preço.
- **Tabela comparativa de especificações**: compara produtos com as colunas:
  - Produto
  - Material
  - Conteúdo do kit
  - Indicação de uso

Quando não há informação no escopo atual do projeto, o campo é preenchido com **"Não informado"**.

## Vídeo HTML5 (MP4/WebM)

Na seção **Produto em Destaque**, foi adicionado um elemento `<video controls>` com duas fontes:

- `videos/loja-2bebeinhos.mp4` (`video/mp4`)
- `videos/loja-2bebeinhos.webm` (`video/webm`)

### Pendência de mídia e teste

- Os arquivos reais de vídeo ainda não estão no repositório.
- A validação de reprodução no navegador permanece pendente até a inclusão dos dois arquivos.

## Estrutura

```text
2bebeinhos/
│
├── index.html
├── README.md
├── videos/
│   └── .gitkeep
│
└── img/
	├── logo-2bebeinhos.png
	│
	└── produtos/
		├── kit-recem-nascido.png
		├── body-pequenos-momentos.png
		├── manta-bebe-conforto.png
		└── kit-hora-do-banho.png
```

## Como executar

Para visualizar o projeto:

1. Clone ou baixe o repositório.
2. Abra a pasta do projeto.
3. Garanta que os vídeos reais estejam em `videos/loja-2bebeinhos.mp4` e `videos/loja-2bebeinhos.webm` (quando disponibilizados).
4. Abra o arquivo `index.html` em um navegador.
5. Navegue pelas seções usando os links internos.
6. Valide o player de vídeo na seção "Produto em Destaque".
7. Não é necessário instalar dependências ou utilizar servidor nesta versão.

## Checklist de requisitos — Entrega 2

- [x] Manter cabeçalho, identidade, produtos, preços, imagens, links internos, carrinho e rodapé.
- [x] Aplicar semântica HTML5 com produtos dentro de `article`.
- [x] Manter navegação principal em `nav > ul > li > a`.
- [x] Incluir categorias em `aside` com lista não ordenada.
- [x] Incluir lista ordenada com passos para escolha de presente.
- [x] Preservar tabela de catálogo.
- [x] Adicionar tabela comparativa com `caption`, `thead` e `tbody`.
- [x] Adicionar vídeo HTML5 com `source` em MP4 e WebM.
- [ ] Validar reprodução no navegador com os dois vídeos reais.

## Validação de requisitos

| Requisito | Status | Arquivo | Evidência |
|---|---|---|---|
| Preservar cabeçalho, identidade, 4 produtos, imagens, links internos, carrinho e rodapé | OK | `index.html` | Estrutura original mantida em `header`, vitrine com 4 `article`, seção `#carrinho` e `footer` |
| Semântica HTML5 (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`) | OK | `index.html` | Estrutura semântica presente em toda a página |
| Navegação principal em `nav > ul > li > a` | OK | `index.html` | Menu principal no `header` mantém a hierarquia solicitada |
| Categorias no `aside` com `ul` | OK | `index.html` | Bloco "Categorias" com quatro itens em lista não ordenada |
| Lista ordenada (`ol`) com 3 passos | OK | `index.html` | Bloco "Como escolher um presente" com 3 passos |
| Preservar tabela de catálogo existente | OK | `index.html` | Seção "Resumo dos produtos" mantida |
| Adicionar tabela comparativa com elementos obrigatórios | OK | `index.html` | Seção "Tabela comparativa de especificações" com `table`, `caption`, `thead`, `tbody`, `tr`, `th`, `td` |
| Vídeo HTML5 no destaque com MP4/WebM | PENDENTE | `index.html` | Elemento `<video>` e `<source>` adicionados; arquivos reais ainda ausentes |
| Teste de reprodução em navegador com arquivos reais | NÃO TESTADO | `index.html` | Depende da inclusão dos vídeos `videos/loja-2bebeinhos.mp4` e `.webm` |

## Roadmap acadêmico

- [x] Versão 1.0 — HTML básico e estrutura do e-commerce
- [x] Versão 2.0 — HTML5 semântico e organização dos dados
- [ ] Versão 3.0 — CSS e identidade visual
- [ ] Versão 4.0 — Layout responsivo com Flexbox/Grid
- [ ] Versão 5.0 — Formulários e checkout
- [ ] Versão 6.0 — JavaScript e carrinho dinâmico

O roadmap poderá ser ajustado conforme o avanço da disciplina.

## ⚠️ Aviso

Este projeto foi criado exclusivamente para fins de estudo e aprendizagem em Desenvolvimento Web. A loja 2bebeinhos apresentada neste repositório é fictícia. Produtos, valores, CNPJ, links e demais informações comerciais são utilizados apenas para simulação acadêmica.

As imagens utilizadas no projeto têm finalidade de composição visual do exercício acadêmico.

## Tecnologias

### Utilizada atualmente

- HTML5

### Previstas nas próximas etapas

- CSS3
- JavaScript
- demais tecnologias previstas pela disciplina, conforme evolução do projeto