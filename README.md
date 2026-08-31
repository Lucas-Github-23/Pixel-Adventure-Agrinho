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

## 🚀 Como Jogar e Executar

### 🎮 Opção 1: Jogar Online no Navegador
Você pode jogar a versão hospedada diretamente no GitHub Pages:

👉 **[Clique aqui para jogar o Pixel Adventure](https://lucas-github-23.github.io/pixel-adventure-agrinho/)**

---

### 💻 Opção 2: Executar Localmente
1. Clone este repositório:
```bash
   git clone [https://github.com/lucas-github-23/pixel-adventure-agrinho.git](https://github.com/lucas-github-23/pixel-adventure-agrinho.git)
```

2. Abra a pasta do projeto e dê um duplo clique no arquivo `index.html` (ou abra utilizando uma extensão de servidor local como o Live Server no VS Code).


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
