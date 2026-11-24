# **Design System — Lavoro Agro**

**Versão 1.0 \| Sistema visual para o site institucional**

O objetivo deste Design System é estabelecer padrões visuais e funcionais para todas as páginas do site da Lavoro Agro, garantindo consistência, facilidade de navegação, boa legibilidade e adaptação a diferentes dispositivos.

A proposta mantém a identidade visual informada pela empresa: verde-escuro, amarelo-dourado, branco, cinza e tons de verde, com Montserrat e Open Sans. Os códigos HEX abaixo são sugestões de especificação para implementação, não uma substituição das cores oficiais. Caso a empresa possua códigos próprios, eles devem prevalecer.

## **1\. Paleta de cores**

**Cores principais**

**Verde-escuro**

\#174D32

Cor primária: cabeçalhos, títulos destacados e botões principais.

**Amarelo-dourado**

\#D6A928

Cor secundária: destaques, ícones e chamadas de atenção.

**Cores complementares**

Branco

\#FFFFFF

Cinza-claro

\#F3F5F3

Verde-claro

\#DDE9DF

Verde médio

\#286344

Verde profundo

\#25332A

Cinza médio

\#6B756D

**Cores funcionais adicionais**

| Aplicação | HEX |
| ----- | ----- |
| Texto principal | `#25332A` |
| Texto secundário | `#6B756D` |
| Bordas | `#DDE3DD` |
| Fundo da página | `#FFFFFF` |
| Fundo alternativo | `#F3F5F3` |
| Sucesso | `#287A45` |
| Erro | `#C43D3D` |
| Aviso | `#B78319` |

**Regras de utilização:**

* Verde-escuro deve ser a cor predominante da identidade.  
* Amarelo-dourado deve ser utilizado com moderação, principalmente em destaques.  
* Branco e cinza-claro devem garantir áreas de descanso visual.  
* Manter contraste suficiente entre texto e fundo para facilitar a leitura.

## **2\. Tipografia**

Serão utilizadas as duas famílias tipográficas definidas na identidade visual.

* **Montserrat:** títulos, subtítulos e chamadas de destaque.  
* **Open Sans:** parágrafos, descrições, formulários, menus e informações gerais.

| Elemento | Fonte | Peso |
| ----- | ----- | ----- |
| Títulos principais | Montserrat | 700 |
| Subtítulos | Montserrat | 600 |
| Títulos de cards | Montserrat | 600 |
| Parágrafos | Open Sans | 400 |
| Botões | Open Sans | 600 |
| Menus | Open Sans | 600 |
| Legendas | Open Sans | 400 |

## **3\. Tamanhos e hierarquia dos textos**

Os tamanhos serão definidos em pixels para facilitar a implementação em CSS.

| Elemento | Desktop | Mobile |
| ----- | ----- | ----- |
| H1 — Título principal | 40 px | 30 px |
| H2 — Título de seção | 32 px | 26 px |
| H3 — Subtítulo | 24 px | 21 px |
| H4 — Título de card | 20 px | 18 px |
| H5 — Título pequeno | 18 px | 16 px |
| Parágrafo | 16 px | 15 px |
| Texto secundário | 14 px | 14 px |
| Legendas | 12 px | 12 px |

**Altura de linha recomendada:**

* Títulos: 1.2.  
* Parágrafos: 1.6.  
* Botões e menus: 1.4.

## **4\. Estilo dos botões**

Os botões devem possuir aparência moderna, simples e de fácil identificação.

**Botão primário**

**Solicitar cotação**

Fundo verde-escuro, texto branco e cantos arredondados.

**Botão secundário**

**Conheça nossos produtos**

Fundo amarelo-dourado, texto escuro.

**Botão de contorno**

**Saiba mais**

Fundo transparente, borda e texto verdes.

**Especificações:**

* Altura padrão: 48 px.  
* Padding horizontal: 20 a 24 px.  
* Raio das bordas: 8 px.  
* Peso da fonte: 600\.  
* Transição: 200 ms.

**Estados dos botões:**

| Estado | Comportamento |
| ----- | ----- |
| Normal | Cor padrão do botão |
| Hover | Escurecimento suave do fundo |
| Focus | Contorno visível para navegação por teclado |
| Active | Leve alteração de tonalidade |
| Disabled | Opacidade reduzida e sem interação |
| Loading | Indicador de carregamento |

## **5\. Estilo dos formulários**

Os formulários devem ser simples, objetivos e acessíveis, principalmente nas páginas de contato e solicitação de cotação.

**Padrões visuais:**

* Altura dos campos: 48 px.  
* Bordas: 1 px sólida.  
* Cor da borda: `#DDE3DD`.  
* Raio: 8 px.  
* Fundo: branco.  
* Texto: `#25332A`.  
* Placeholder: `#6B756D`.  
* Espaçamento entre campos: 16 px.

**Estados dos campos:**

| Estado | Aparência |
| ----- | ----- |
| Normal | Borda cinza-clara |
| Focus | Borda verde-escura |
| Erro | Borda vermelha e mensagem explicativa |
| Sucesso | Indicação visual verde |
| Disabled | Fundo cinza-claro |

**Campos reutilizáveis:**

* Nome completo.  
* E-mail.  
* Telefone.  
* Cidade e estado.  
* Categoria de produto.  
* Produto desejado.  
* Mensagem ou descrição da necessidade.

Os campos devem possuir rótulos visíveis, validação e mensagens de orientação.

## **6\. Cards e elementos reutilizáveis**

Os cards serão utilizados para organizar produtos, conteúdos, representantes e informações institucionais.

[COOPERATIVA AGROPECUÁRIA PIONEIRA LTDA](https://images.openai.com/static-rsc-4/aikK49YC_t7SgeWA4k-TzeC9TMNJuIq8jzvV87lq6lZk5AEuO-WLTsG_WvH3nzgc-qhdCo60gkcRvH1w2-FYDo5nAj4wQcbMWQ8wOmrJ-9a_hL5QyDDMEIZ_hyqfRU0cTiiC7x3d5ZJnWBLoLd406CrfTiYcYltgC6XQG_Tirus?purpose=inline)

**Card de produto**

Sementes e soluções agrícolas.

**Ver detalhes →**

[Put Your "Drones" Up In The Air: Drones in Agriculture And Where We Use Them](https://images.openai.com/static-rsc-4/9EL6U0Am7irJdgbLgM0hVzws7b7L4ds1dT6xtvTztpT1n586kzqpTsDLrrvhbmni0MW_wkSBMRY8xFbb2G_G-WHQdt5JUt-32xuu26Fzx5K72_3SAARnCivX-vZDtggCeQUJq9nQXRhZGvl0q4WgC2njf0jDlld815uQ4o4CwXk?purpose=inline)

**Card de conteúdo**

Artigos e informações técnicas.

**Ler conteúdo →**

**Padrões dos cards:**

* Fundo branco.  
* Borda cinza-clara.  
* Raio de 12 px.  
* Espaçamento interno de 16 a 24 px.  
* Imagens com proporção consistente.  
* Título em Montserrat.  
* Descrição em Open Sans.  
* Botão ou link de ação.

Outros componentes reutilizáveis:

* Cards de representantes técnicos (RTVs).  
* Cards de unidades da empresa.  
* Cards de cotações de commodities.  
* Cards de benefícios e diferenciais.  
* Cards de notícias e artigos.

## **7\. Bordas, sombras e espaçamentos**

**Bordas**

* Campos e elementos simples: 1 px.  
* Cards: 1 px.  
* Botões: sem borda ou com borda de 1 px.  
* Raio pequeno: 4 px.  
* Raio padrão: 8 px.  
* Raio de cards: 12 px.  
* Raio de grandes contêineres: 16 px.

**Sombras**

| Elemento | Sombra sugerida |
| ----- | ----- |
| Cards | `0 2px 8px rgba(0,0,0,0.06)` |
| Menus suspensos | `0 4px 12px rgba(0,0,0,0.10)` |
| Modais | `0 8px 24px rgba(0,0,0,0.12)` |

**Escala de espaçamento**

Utilizar uma escala baseada em múltiplos de 4 px.

| Token | Valor |
| ----- | ----- |
| `space-1` | 4 px |
| `space-2` | 8 px |
| `space-3` | 12 px |
| `space-4` | 16 px |
| `space-5` | 20 px |
| `space-6` | 24 px |
| `space-8` | 32 px |
| `space-10` | 40 px |
| `space-12` | 48 px |
| `space-16` | 64 px |
| `space-20` | 80 px |

## **8\. Regras de responsividade**

O site deverá funcionar corretamente em computadores, tablets e smartphones.

| Dispositivo | Largura de referência | Comportamento |
| ----- | ----- | ----- |
| Mobile | Até 767 px | Layout em uma coluna |
| Tablet | 768–1023 px | Layout adaptado, geralmente duas colunas |
| Desktop | 1024–1279 px | Layout amplo |
| Desktop grande | 1280 px ou mais | Conteúdo centralizado |

**Regras gerais:**

* Menu principal transformado em menu compacto no mobile.  
* Imagens adaptadas à largura da tela.  
* Cards empilhados em telas pequenas.  
* Formulários organizados em uma coluna no mobile.  
* Botões com área de toque confortável.  
* Títulos ajustados conforme o dispositivo.  
* Evitar rolagem horizontal.  
* Manter os principais CTAs visíveis e acessíveis.

## **9\. Componentes que deverão ser reutilizados nas páginas**

Para garantir consistência e facilitar futuras alterações, os seguintes componentes deverão ser desenvolvidos uma única vez e reutilizados no site.

| Componente | Aplicação |
| ----- | ----- |
| Header | Cabeçalho e navegação |
| Menu mobile | Navegação em smartphones |
| Footer | Rodapé institucional |
| Button | Botões de ação |
| Input | Campos de formulário |
| Select | Seleção de opções |
| Textarea | Campo de mensagem |
| ProductCard | Catálogo de produtos |
| ContentCard | Notícias e artigos |
| RTVCard | Representantes técnicos |
| UnitCard | Unidades da empresa |
| CommodityCard | Cotações de mercado |
| Breadcrumb | Caminho de navegação |
| SectionTitle | Títulos de seções |
| SearchBar | Busca de produtos e conteúdos |
| FilterBar | Filtros do catálogo |
| Modal | Janelas de confirmação |
| Alert | Mensagens de erro e sucesso |
| Pagination | Navegação entre páginas |
| CTASection | Seções de chamada para ação |

Esses componentes serão utilizados nas páginas de Início, Sobre, Produtos, Detalhes do Produto, Solicitação de Cotação, Encontre seu RTV, Conteúdos, Mercado e Contato.

## **10\. Organização para implementação em CSS**

Abaixo está uma base de variáveis CSS que poderá ser utilizada posteriormente no desenvolvimento do site.

```

:root {
  /* Cores principais */
  --color-primary: #174D32;
  --color-secondary: #D6A928;

  /* Cores complementares */
  --color-white: #FFFFFF;
  --color-gray-light: #F3F5F3;
  --color-gray-medium: #6B756D;
  --color-border: #DDE3DD;

  --color-green-light: #DDE9DF;
  --color-green-medium: #286344;
  --color-green-dark: #25332A;

  /* Cores funcionais */
  --color-success: #287A45;
  --color-error: #C43D3D;
  --color-warning: #B78319;

  /* Tipografia */
  --font-heading: "Montserrat", sans-serif;
  --font-body: "Open Sans", sans-serif;

  /* Tamanhos */
  --text-xs: 12px;
  --text-sm: 14px;
  --text-base: 16px;
  --text-lg: 18px;
  --text-xl: 20px;
  --text-2xl: 24px;
  --text-3xl: 32px;
  --text-4xl: 40px;

  /* Bordas */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 12px;
  --radius-xl: 16px;

  /* Espaçamentos */
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 12px;
  --space-4: 16px;
  --space-6: 24px;
  --space-8: 32px;
  --space-12: 48px;
  --space-16: 64px;

  /* Sombras */
  --shadow-card: 0 2px 8px rgba(0,0,0,0.06);
  --shadow-modal: 0 8px 24px rgba(0,0,0,0.12);
}
```

## **11\. Diretrizes finais do Design System**

1. Não modificar o logotipo oficial da Lavoro Agro.  
2. Não substituir as cores institucionais por cores de outras identidades.  
3. Manter Montserrat nos títulos e Open Sans nos textos.  
4. Utilizar os mesmos padrões de botões, formulários e cards em todas as páginas.  
5. Priorizar a experiência do produtor rural, com navegação simples e informações claras.  
6. Garantir acessibilidade, legibilidade e responsividade.  
7. Manter consistência visual em todas as páginas e dispositivos.

**Resultado esperado:** um sistema visual padronizado, organizado e reutilizável, que servirá como referência para a criação das telas no Figma e, posteriormente, para a implementação do site em CSS ou Tailwind CSS.

