# 🛠️ Pixel Adventure (Agrinho)

![Game Banner / Icon](icon-256.png)

> **Pixel Adventure** é um jogo de plataforma 2D em Pixel Art desenvolvido para o **Programa Agrinho**. O jogo combina diversão, mecânicas clássicas de plataforma e uma experiência educativa focada no aprendizado interativo de crianças e jovens.

---

## 📋 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [🎮 Mecânicas e Funcionalidades](#-mecânicas-e-funcionalidades)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [🚀 Como Executar o Jogo](#-como-executar-o-jogo)
- [📁 Estrutura de Arquivos](#-estrutura-de-arquivos)
- [📜 Licença e Créditos](#-licença-e-créditos)

---

## 🌾 Sobre o Projeto

O projeto foi criado originalmente como parte do **Programa Agrinho**, iniciativa que promove a conscientização sobre o meio ambiente, ética, cidadania e trabalho no campo. 

O jogador explora fases dinâmicas enquanto supera desafios, derrota inimigos e coleta recursos, unindo a nostalgia dos jogos clássicos de plataforma em 8/16-bits a mensagens de conscientização.

---

## 🎮 Mecânicas e Funcionalidades

- **Movimentação Clássica:** Sistema fluído de corrida, pulo, pulo duplo e física de plataforma.
- **Inimigos & Chefões:**
  - Inimigos normais (Galinha, Cogumelo, etc.) com comportamentos variados.
  - Enfrentamento de **Bosses** com barra de vida e padrões de ataque únicos.
- **Armadilhas & Desafios:** Plataformas móveis, espinhos, plataformas que caem e trampolins.
- **Coletáveis:** Frutas e itens espalhados pela fase para somar pontuação.
- **Progressão de Fases:** Menu de seleção de fases travado/destravado (*Padlock System*).
- **Interface & Sons:** Efeitos sonoros imersivos, música de fundo (`caketown.ogg`) e suporte a áudio configurável.
- **Suporte PWA / Offline:** Execução direta no navegador e suporte para funcionamento offline via Service Workers (`sw.js`).

---

## 🛠️ Tecnologias Utilizadas

O jogo foi construído utilizando a engine de jogos HTML5 **Construct 2/3**:

- **HTML5 / CSS3 / JavaScript (ES6)**
- **Construct Runtime (`c2runtime.js`)**
- **jQuery 3.4.1**
- **Web Audio API & Canvas API**
- **Service Worker API** (suporte PWA)

---

## 🚀 Como Executar o Jogo

Como o jogo foi exportado em HTML5 Web, você não precisa instalar nenhuma engine para jogar!

### Opção 1: Executar Localmente
1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/seu-usuario/Pixel-Adventure-Agrinho.git
   ```
2. Abra a pasta do projeto e dê um duplo clique no arquivo `index.html` (ou abra via servidor local como Live Server no VS Code).

### Opção 2: Hospedar no GitHub Pages / Netlify / Vercel
1. Faça o upload deste repositório para o seu GitHub.
2. Ative o **GitHub Pages** nas configurações do repositório (`Settings > Pages`).
3. O jogo estará disponível online e jogável em qualquer navegador ou celular!

---

## 📁 Estrutura de Arquivos

```text
├── icon-*.png               # Ícones da aplicação para PWA/Navegador
├── images/                  # Sprites, cenários, inimigos, chefões e interface
├── media/                   # Efeitos sonoros e músicas do jogo (.m4a, .ogg)
├── index.html               # Ponto de entrada do jogo
├── c2runtime.js             # Motor de execução do jogo
├── data.js                  # Lógica de fases e eventos
├── sw.js / offline.js       # Configurações para suporte offline (PWA)
└── README.md                # Documentação do projeto
```

---

## 📜 Licença e Créditos

- **Desenvolvimento:** Projeto desenvolvido para o Programa Agrinho.
- **Arte / Assets:** Pixel Art e Sprites adaptados do pacote *Pixel Adventure* por [Pixel Frog](https://pixelfrog-assets.itch.io/).
