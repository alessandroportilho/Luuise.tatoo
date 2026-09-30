# luuise.ink | Portfólio Oficial 🖤

Repositório oficial do portfólio e site profissional da tatuadora **Luise**, localizado em Campo Grande, Rio de Janeiro - RJ.

🌐 **Acesse o site online:** [https://luuisetatoo.github.io/](https://alessandroportilho.github.io/Luuise.tatoo/)

---

## 🚀 O que foi alterado e otimizado recentemente?

Nesta última atualização, o site passou por uma grande melhoria de performance, estruturação técnica e otimização para motores de busca (SEO):

### 1. 🔍 Otimização de SEO Completa
* **Metatags Avançadas:** Adicionada descrição detalhada, palavras-chave focadas na região (Campo Grande, RJ) e estilos de tatuagem (*Blackwork*, *Fineline*, *Realismo*)[cite: 3].
* **Open Graph (OG) e Twitter Cards:** Configuração completa de cartões de compartilhamento para redes sociais (WhatsApp, Instagram, Facebook, X), garantindo que o site exiba o título correto, descrição e imagem de pré-visualização (`preview.webp`)[cite: 3].
* **Dados Estruturados (Schema.org):** Inclusão de um script JSON-LD do tipo `TattooParlor` para ajudar o Google a indexar o estúdio como um negócio local, facilitando a aparição em buscas locais[cite: 3].
* **Canonical Tags e Região:** Configuração de tags canônicas e metatags geográficas (`geo.region` e `geo.placename`)[cite: 3].

### 2. ⚡ Performance e Mídia para a Web
* **Conversão para WebP:** Todas as imagens principais (`tatooestudio1.webp`, `tatuadora.webp`, o favicon e os itens do portfólio) foram convertidas para o formato moderno `.webp`, reduzindo drasticamente o tempo de carregamento da página[cite: 3].
* **Lazy Loading:** Implementação do atributo `loading="lazy"` nas imagens abaixo da dobra para carregar os elementos apenas conforme o usuário faz o scroll na página[cite: 3].
* **Organização de Pastas:** Estruturação profissional dos arquivos multimédia em pastas dedicadas (`/assets/img/` para imagens e `/assets/video/` para futuros vídeos)[cite: 3].

### 3. 🎨 Correções de Design e Experiência do Usuário (UX)
* **Correção de Legibilidade:** Ajuste nas cores dos textos da barra de navegação (`navbar`) para garantir contraste perfeito sobre o fundo escuro e efeito translúcido (*backdrop-blur*)[cite: 3].
* **Identidade Preservada:** Mantido todo o design original em Tailwind CSS, incluindo o menu mobile responsivo, o efeito de texto rotativo (*Word Rotator*) no título principal e as animações suaves de revelação ao rolar a página (*Reveal on Scroll*)[cite: 3].

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** (Semântico e Otimizado para SEO)
* **Tailwind CSS** (Via CDN para estilização rápida e responsiva)
* **JavaScript (Vanilla)** (Para interatividade, menu mobile e Intersection Observer)
* **Font Awesome** (Ícones para redes sociais e marcações)
* **Google Fonts** (Inter & Playfair Display)

---

## 📂 Estrutura de Pastas do Projeto

```text
/luisetatoo_github.io
│-- index.html             # Página principal otimizada
│-- README.md              # Documentação do projeto
└── /assets
    ├── /img               # Imagens otimizadas em formato .webp (portfólio, estúdio, favicon)
    └── /video             # Arquivos de vídeo otimizados para o portfólio
