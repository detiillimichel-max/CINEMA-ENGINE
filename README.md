# CINEMA-ENGINE

Estúdio cinematográfico procedural. O primeiro experimento, **O DESPERTAR**, é um curta de 30 segundos desenhado em tempo real com HTML, CSS, JavaScript e Canvas 2D.

## Primeiro teste

- Abra: https://detiillimichel-max.github.io/CINEMA-ENGINE/
- Toque em **Iniciar filme**.
- Use pausar, continuar, reiniciar e a barra de progresso.
- Não há MP4, imagens, vídeos, bibliotecas ou arquivos externos.

## Arquitetura

O navegador desenha os quadros em tempo real. O repositório guarda apenas o código-fonte. O GitHub Actions executa uma validação automática a cada alteração do filme e também pode ser iniciado manualmente.

## Limites desta prova

Este teste comprova a reprodução de uma animação procedural simples, não a capacidade de produzir cinema fotorrealista. O áudio não está incluído nesta primeira versão. O desempenho depende do navegador e do aparelho.

## Próximas etapas

1. Testar em celular Android.
2. Medir fluidez e consumo de memória.
3. Separar cenas, câmera, personagens e trilha em módulos.
4. Evoluir para SVG, Canvas avançado e WebGL/Three.js quando necessário.
