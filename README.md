# Drone Game

Um jogo de drone onde o jogador controla um drone para identificar e coletar alvos usando diferentes bandas de radar.

## Características

- **Dimensões**: 90mm x 70mm (340x264 pixels)
- **Controle**: Teclado e mouse/touch
- **Bandas**: C (identificação), L (alvo laranja), P (alvo marrom)

## Como Jogar

- Use as setas esquerda/direita para mover o drone
- Pressione 1, 2, 3 para alternar entre bandas C, L e P
- Pressione espaço para ativar o feixe de radar
- Colete os alvos correspondentes à banda ativa
- Use a banda C para marcar árvores permanentemente com contorno dourado

## Funcionalidades

- Paisagem em movimento contínuo com árvores realistas
- Sistema de marcação permanente de árvores com banda C
- Alvos aparecem aleatoriamente
- Sistema de inventário para cada banda
- Suporte a dispositivos móveis com controles touch
- Design responsivo
- Renderização de alta qualidade para imagens

## Arquivos

- `index.html`: Arquivo principal do jogo
- `drone.png`: Imagem do drone
- `formiga.png`: Imagem da formiga (alvo P)
- `arvore1.png`: Imagem das árvores normais
- `arvore11.png`: Imagem das árvores marcadas com banda C
- `fundo.png`: Imagem de fundo do cenário (repetida como padrão)

## Desenvolvimento

O jogo foi desenvolvido usando HTML5 Canvas, JavaScript ES6 e CSS3. Inclui otimizações de performance como redesenho condicional e constantes para manutenção.

## Mobile

O jogo detecta automaticamente dispositivos móveis e ativa controles touch:
- Botões virtuais para movimento
- Botão para ativar feixe
- Layout adaptado para telas menores