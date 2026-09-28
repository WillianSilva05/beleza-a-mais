# 🌿 Beleza a Mais — Cuidados Pessoais & Bem-Estar

## 📌 1. Proposta Visual

### Conceito da Loja
A **Beleza a Mais** é uma loja especializada em cosméticos de cuidados pessoais, autocuidado consciente e bem-estar (sabonetes artesanais, cremes hidratantes, sérum facial e óleos corporais). O objetivo visual é criar uma atmosfera de **acolhimento, tranquilidade e conforto**, reproduzindo a experiência relaxante de um spa botânico.

### Psicologia das Cores para Beleza & Bem-Estar
* **Rosa Terracota Blush (`#C87A6D`):** Transmite carinho, sensibilidade e cuidado com a pele, conectando o cliente ao ritual diário de autocuidado.
* **Verde Sálvia Botânico (`#5E7D63`):** Evoca ingredientes vegetais, sustentabilidade e frescor natural.
* **Tons de Fundo Areia / Creme Suave (`#FAF6F3`):** Proporciona descanso visual, destacando as fotos e informações sem poluição visual.
* **Gradientes Suaves:** Aplicados em banners, cartões e botões para um acabamento moderno e acetinado.

### Identidade Visual & Logotipo (Monograma Serifado)
* **Monograma "B" Clássico:** O logotipo oficial traz a letra inicial "B" desenhada com haste vertical sólida, serifas elegantes de perfumaria fina e acabamento rosé gold, acompanhada de um raminho botânico e brilho dourado champagne.
* **Harmonia Completa:** O logotipo do cabeçalho (`imagens/logo.svg`) e o favicon da aba do navegador (`imagens/favicon.svg`) compartilham o mesmo símbolo e paleta de cores.

### Público-Alvo
* Pessoas de todas as idades que valorizam rotinas de cuidados pessoais, produtos com formulações vegetais e bem-estar.
* Clientes que buscam uma experiência de navegação online simples, intuitiva, agradável e perfeitamente responsiva.

---

## 🎨 2. Guia de Estilo

### Paleta de Cores Utilizada

| Cor / Finalidade | Código HEX | Código RGB | Aplicação no Projeto |
| :--- | :--- | :--- | :--- |
| **Primária (Terracota Blush)** | `#C87A6D` | `rgb(200, 122, 109)` | Logotipo, links ativos, títulos e botões |
| **Primária Escura (Hover)** | `#A6584C` | `rgb(166, 88, 76)` | Efeito ao passar o mouse em botões e links |
| **Verde Sálvia (Botânico)** | `#5E7D63` | `rgb(94, 125, 99)` | Selos de destaque dos produtos e sustentabilidade |
| **Dourado Champagne** | `#D4A373` | `rgb(212, 163, 115)` | Detalhes sutis no monograma e acabamentos |
| **Fundo da Página (Creme/Areia)** | `#FAF6F3` | `rgb(250, 246, 243)` | Cor de fundo geral do site (`body`) |
| **Branco Puro (Superfície)** | `#FFFFFF` | `rgb(255, 255, 255)` | Superfície dos cartões e formulário |
| **Bordas Delicadas** | `#EADED7` | `rgb(234, 222, 215)` | Divisores e contornos sutis |
| **Texto Principal (Grafite Amadeirado)**| `#332924` | `rgb(51, 41, 36)` | Textos principais com alto contraste |
| **Texto Secundário** | `#6E615A` | `rgb(110, 97, 90)` | Descrições e textos de apoio |
| **Fundo do Rodapé** | `#2B2420` | `rgb(43, 36, 32)` | Fundo elegante e escuro do rodapé |

### Tipografia Escolhida
Utilização de **fontes nativas e seguras para a web (Web Safe Fonts)**, garantindo carregamento instantâneo em qualquer navegador:
* **Títulos e Logotipo:** `Georgia, 'Times New Roman', serif` (confere sofisticação, requinte e identidade de boutique).
* **Textos, Menus e Botões:** `Arial, Helvetica, sans-serif` (excelente legibilidade e clareza visual).

---

## 💻 3. Tecnologias Utilizadas

* **HTML5 Semântico:** Estrutura organizada com tags semânticas obrigatórias (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<address>`, `<form>`), todas devidamente comentadas explicando seus blocos estruturais.
* **CSS3 Customizado (`css/style.css`):**
  * **Variáveis CSS (`:root`)** para centralização de todas as cores e gradientes;
  * **Gradientes Lineares (`linear-gradient`)** aplicados no banner hero, cartões e botões;
  * **Flexbox** para o layout da vitrine, alinhamento dos menus e divisão da página de contato;
  * **Media Queries (`@media`)** garantindo responsividade em celulares, tablets e computadores;
  * Comentários explicativos organizando cada seção de regras de estilo.
* **Suporte de Framework (Bootstrap 5 via CDN):**
  * Utilizado de forma opcional (conforme autorizado no enunciado) especificamente para o **Carrossel Responsivo** (`#carrosselProdutos`) na página inicial (`index.html`), mantendo todo o estilo visual sob controle do `style.css`.

---

## 📁 4. Estrutura de Pastas do Projeto

O projeto segue fielmente o padrão de organização recomendado na atividade:

```text
PortifolioPW/
├── css/
│   └── style.css          # Folha de estilos customizada e comentada
├── imagens/
│   ├── favicon.svg        # Ícone de favoritos da aba (monograma B)
│   ├── logo.svg           # Logotipo vetorial oficial (monograma B serifado)
│   ├── sabonete-vegetal.png # Foto realista: aveia, lavanda e camomila
│   ├── serum-facial.png     # Foto realista: frasco conta-gotas e gotículas
│   ├── creme-corporal.png   # Foto realista: pote de amêndoas e karité
│   ├── oleo-corporal.png    # Foto realista: óleo dourado iluminado
│   └── balsamo-labial.png   # Foto realista: latinha botânica e rosas
├── index.html             # Início com Carrossel Bootstrap e Sobre Nós
├── produtos.html          # Vitrine completa com os 5 produtos e preços
├── contato.html           # Formulário estilizado, dados institucionais e mapa
├── portifolio2.pdf        # Documento oficial com as diretrizes do professor
└── README.md              # Documentação técnica completa
```

---

## 🚀 5. Como Visualizar o Projeto

1. Abra o arquivo `index.html` em qualquer navegador (Chrome, Edge, Firefox, etc.).
2. Observe o monograma elegante combinando no cabeçalho e na aba do navegador.
3. Veja o carrossel interativo no topo alternando entre os produtos em destaque.
4. Navegue para a página de **Produtos** para conferir a vitrine completa com os cartões e novos gradientes.
5. Acesse a página de **Contato** para testar o formulário e a localização com mapa.
