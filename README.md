# 🚀 2bebeinhos

Loja virtual fictícia de presentes e produtos para bebês, desenvolvida como projeto evolutivo para estudo de Desenvolvimento Web.

> Presentes para celebrar os pequenos grandes momentos.

A identidade visual do projeto utiliza o conceito de dois bebês e uma temática espacial, que será desenvolvida gradualmente nas próximas etapas.

## Objetivo acadêmico

O objetivo é desenvolver progressivamente uma loja virtual enquanto são estudados conceitos de desenvolvimento web. O projeto será construído em etapas, permitindo acompanhar sua evolução desde uma página HTML básica até versões com estilização, responsividade e programação.

## 📌 Versão atual — 3.0

A versão 3.0 mantém a estrutura HTML5 semântica da V2.0 e adiciona formulários de coleta de dados com os métodos GET e POST. A entrega não utiliza CSS, JavaScript, backend ou pagamentos reais.

Objetivos desta etapa:

- praticar a estrutura semântica do HTML5;
- utilizar corretamente `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`;
- organizar a navegação em listas HTML;
- utilizar listas não ordenadas para categorias e listas ordenadas para instruções;
- promover uma hierarquia clara de títulos;
- apresentar uma tabela estruturada com dados do catálogo;
- comparar especificações de produtos em uma segunda tabela;
- utilizar vídeo HTML5 com formatos MP4 e WebM;
- manter a identidade do projeto acadêmico e os elementos já estudados na versão anterior.

**Tecnologia utilizada:**
- HTML5

**CSS, JavaScript e backend continuam como tecnologias futuras.**

## Funcionalidades simuladas

A versão 3.0 mantém:

- identificação da loja;
- navegação interna por seções;
- vitrine de produtos com quatro itens;
- destaque do Kit Presente Recém-Nascido;
- simulação de carrinho através de âncoras HTML;
- informações e atendimento fictícios no rodapé;
- organização semântica e acessível do conteúdo.
- formulários acadêmicos de busca GET e cadastro/pedido POST.

O carrinho continua sem lógica real. Ele serve apenas para simular a navegação entre partes da página utilizando HTML.

## Estrutura

```text
2bebeinhos/
│
├── index.html
├── README.md
│
├── img/
	├── logo-2bebeinhos.png
	│
	└── produtos/
		├── kit-recem-nascido.png
		├── body-pequenos-momentos.png
		├── manta-bebe-conforto.png
		└── kit-hora-do-banho.png

└── videos/
	├── 2bebeinhos-apresentacao.webm
	└── 2bebeinhos-apresentacao.mp4
```

Os arquivos MP4 e WebM estão disponíveis na pasta `videos/` e foram testados localmente em um navegador.

## Como executar

Para visualizar o projeto:

1. Clone ou baixe o repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.
4. Não é necessário instalar dependências ou utilizar um servidor nesta versão.

Para validar a reprodução dos vídeos, abra o `index.html` por um servidor local ou pela extensão Live Server.

## Roadmap acadêmico

- [x] Versão 1.0 — HTML básico e estrutura do e-commerce
- [x] Versão 2.0 — HTML5 semântico, listas, tabelas comparativas e vídeo demonstrativo
- [x] Versão 3.0 — Formulários GET e POST
- [ ] Versão 4.0 — CSS e identidade visual
- [ ] Versão 5.0 — Layout responsivo com Flexbox/Grid
- [ ] Versão 6.0 — Formulários e checkout integrado
- [ ] Versão 7.0 — JavaScript e carrinho dinâmico

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

## Versão 3.0 — Formulários GET e POST

A Versão 3.0 amplia o projeto acadêmico com formulários HTML5 para demonstrar a coleta de dados e a diferença entre os métodos HTTP GET e POST. Esta etapa continua sem CSS, JavaScript, backend ou pagamentos reais.

### Formulário de busca GET

O formulário de busca utiliza `action="index.html"` e `method="get"`. Ele possui um campo de busca textual e um filtro de categoria. Depois do envio, os valores aparecem na URL como parâmetros, por exemplo:

```text
index.html?q=manta&categoria=mantas
```

Essa demonstração não filtra o catálogo automaticamente, pois isso exigiria uma implementação funcional adicional.

### Formulário de cadastro e pedido POST

O formulário de cadastro e finalização utiliza `action="processa-pedido.html"` e `method="post"`. Ele contém:

- dados pessoais e de acesso;
- quantidade do pedido e opções de frete;
- forma de pagamento sem solicitar dados reais de cartão;
- aceite obrigatório dos termos e preferência opcional de ofertas;
- campo de observações para entrega;
- botões para finalizar ou limpar o formulário.

Os campos possuem `label`, identificadores únicos, agrupamento com `fieldset` e `legend`, além de validações nativas como e-mail, campos obrigatórios e limites de quantidade.

Uma página HTML estática não processa uma requisição POST automaticamente. Portanto, `processa-pedido.html` é apenas o destino acadêmico definido para demonstrar o formulário. Nenhuma senha ou dado pessoal é armazenado e não há confirmação real de compra.

### Como testar os formulários

Para testar o GET:

1. Abra o projeto por um navegador ou servidor local.
2. Digite um produto, selecione uma categoria e clique em **Buscar**.
3. Confira na barra de endereço os parâmetros `q` e `categoria`.

Para inspecionar o POST:

1. Abra as ferramentas de desenvolvedor do navegador com `F12`.
2. Acesse a aba **Network** ou **Rede**.
3. Preencha os campos obrigatórios e clique em **Finalizar Pedido**.
4. Selecione a requisição e confira o método `POST`, o destino `processa-pedido.html` e os dados enviados no corpo da requisição.

O envio pode apresentar erro de destino porque não existe backend nesta etapa. Isso é esperado e não representa uma compra funcional. Não utilize dados pessoais reais durante os testes.

### Checklist da Parte 3

- [x] Formulário de busca com método GET
- [x] Campo `search`, filtro `select` e botão de busca
- [x] Formulário de cadastro e pedido com método POST
- [x] Campos pessoais, quantidade, frete e pagamento
- [x] Checkboxes de termos e ofertas
- [x] Campo de observações com `textarea`
- [x] Botões de envio e redefinição
- [x] Labels, IDs únicos, fieldsets e legends
- [x] Validações nativas HTML5
- [x] Limitação do POST estático documentada
- [ ] Processamento real do pedido, reservado para uma etapa futura

## Checklist da V2.0

- [x] Estrutura com elementos semânticos do HTML5
- [x] Navegação principal com `nav`, `ul`, `li` e links internos
- [x] Produtos organizados em `article`
- [x] Categorias em lista não ordenada
- [x] Passos para escolher um presente em lista ordenada
- [x] Tabela de catálogo preservada
- [x] Tabela comparativa de especificações adicionada
- [x] Vídeo MP4 adicionado
- [x] Vídeo WebM adicionado
- [x] Reprodução do vídeo testada em navegador