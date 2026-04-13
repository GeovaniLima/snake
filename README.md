# Snake Arcade

Jogo da cobrinha classico com visual estilo arcade retro, efeito CRT e estetica neon.

## Como jogar

1. Abra o arquivo `index.html` no navegador
2. Pressione qualquer tecla para iniciar
3. Controle a cobra e coma a comida vermelha para crescer
4. Evite bater nas paredes e no proprio corpo

## Controles

| Tecla | Acao |
|-------|------|
| Setas (direcional) | Mover a cobra |
| W A S D | Mover a cobra (alternativo) |
| Qualquer tecla | Iniciar / Reiniciar |

Em dispositivos mobile, um D-pad touch aparece automaticamente.

## Funcionalidades

- Velocidade aumenta progressivamente conforme a pontuacao
- High score salvo localmente no navegador (localStorage)
- Efeitos visuais: scanlines CRT, vinheta, brilho fosforescente, comida pulsante
- Cobra com olhos que seguem a direcao do movimento
- Suporte a teclado e touch (mobile)

## Tecnologias

- HTML5 Canvas
- CSS3
- JavaScript (vanilla)

## Estrutura

```
Snake/
  index.html   # Arquivo unico com todo o jogo (HTML + CSS + JS)
  README.md
```
