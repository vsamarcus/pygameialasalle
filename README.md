# Demo de Animação de Sprite com Movimento

Uma demonstração simples em PyGame apresentando uma animação de sprite com movimento controlado por teclado e detecção de colisão.

## Pré-requisitos

- Python 3.x
- Biblioteca PyGame

## Instalação

1. Instale o PyGame se ainda não tiver instalado:
```bash
pip install pygame
```

2. Certifique-se de ter a folha de sprites necessária:
   - Arquivo chamado `Attack.png` no mesmo diretório do script
   - A folha de sprites deve conter 8 quadros de animação

## Executando o Programa

Execute o script usando Python:
```bash
python janelaComSpriteMovimentacaoXY.py
```

## Controles

- **Teclas de Seta**: Movimentam o sprite
  - ↑ (Seta para Cima): Move para cima
  - ↓ (Seta para Baixo): Move para baixo
  - ← (Seta para Esquerda): Move para esquerda
  - → (Seta para Direita): Move para direita
- **Sair**: Clique no botão "Sair" ou feche a janela

## Funcionalidades

- Sprite animado com 8 quadros
- Movimento suave em todas as direções
- Detecção de colisão com as bordas da tela
- Detecção de colisão com o botão central
- Janela de 1000x500 pixels
