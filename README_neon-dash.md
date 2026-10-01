# ⚡ Neon Dash

Protótipo de *endless runner* 2D desenvolvido com **PixiJS**, com física de pulo, gravidade e dificuldade progressiva.

**[▶ Jogar online](https://claude.ai/artifact/YbW14YUoLb6XVKJSsHmq6A)**

![status](https://img.shields.io/badge/status-prot%C3%B3tipo-9b5cff) ![engine](https://img.shields.io/badge/engine-PixiJS-5affd6)

## Sobre o projeto

Segundo protótipo de uma pequena série de experimentos pessoais com desenvolvimento de jogos 2D na web. Enquanto o [Horde Survivor](../horde-survivor) explora combate e mira, o **Neon Dash** tem um foco diferente: **física, timing e progressão de dificuldade**, mecânicas centrais em jogos de plataforma e corrida infinita.

O objetivo foi praticar, do zero, com PixiJS puro:

- Simulação de gravidade e física de pulo
- Game loop com velocidade de jogo crescente ao longo do tempo
- Geração procedural de obstáculos, com intervalo variável
- Detecção de colisão via bounding box (AABB)
- HUD reativo com distância percorrida, velocidade atual e recorde

## Como jogar

- **Pular:** `Espaço` (teclado) ou toque na tela
- **Objetivo:** desvie dos obstáculos pulando no momento certo. A velocidade aumenta continuamente — sobreviva o máximo de distância possível.

## Tecnologias

| Tecnologia | Uso |
|---|---|
| **PixiJS** | Renderização 2D via WebGL/Canvas |
| **JavaScript** | Física de jogo (gravidade, pulo), geração de obstáculos e colisão |
| **HTML/CSS** | Estrutura, HUD e responsividade |

## Mecânicas implementadas

- Física simples de gravidade e salto (velocidade vertical acumulada por frame)
- Velocidade de jogo crescente ao longo da partida, aumentando a dificuldade
- Geração de obstáculos com intervalo decrescente conforme a velocidade sobe
- Colisão por bounding box entre jogador e obstáculos
- Tela de game over com distância percorrida e recorde da sessão

## Rodando localmente

Projeto em arquivo único, sem dependências de build:

```bash
git clone <url-do-repositorio>
cd neon-dash

open index.html   # ou dê duplo clique no arquivo
```

## Próximos passos (ideias de evolução)

- [ ] Sprites animados para personagem e obstáculos
- [ ] Variação de padrões de obstáculo (combos, alturas diferentes)
- [ ] Efeitos visuais de parallax no cenário
- [ ] Persistência de recorde (localStorage)
- [ ] Som e feedback de impacto

## Autor

**Daniel Pereira Carli**
[LinkedIn](https://www.linkedin.com/in/daniel-pereira-carli-9b00a9270/) · [GitHub](https://github.com/DanielCarli88)
