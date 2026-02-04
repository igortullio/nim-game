# Jogo do Nim

Implementação em Python do clássico Jogo do Nim, onde o computador utiliza uma estratégia matemática baseada em teoria dos jogos para vencer o jogador.

## Sobre

O Jogo do Nim consiste em **n** peças dispostas em um tabuleiro, onde dois jogadores alternam turnos retirando entre 1 e **m** peças por rodada. Quem retirar as últimas peças vence.

O computador segue a estratégia ótima: sempre deixar um número de peças que seja múltiplo de **(m+1)** para o oponente, garantindo a vitória quando matematicamente possível.

## Funcionalidades

- Partida individual contra o computador
- Modo campeonato (melhor de 3 rodadas)
- Estratégia vencedora baseada em teoria dos jogos
- Validação de jogadas do usuário
- Decisão automática de quem inicia com base na vantagem estratégica

## Como executar

```bash
python3 jogo_nim.py
```

## Exemplo

```
Bem-vindo ao jogo do NIM! Escolha:

1 - para jogar uma partida isolada
2 - para jogar um campeonato

Quantas peças? 3
Limite de peças por jogada? 1

Computador começa!
O computador tirou uma peça.
Agora restam 2 peças no tabuleiro.
```

## Tecnologias

- Python 3