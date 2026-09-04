# LP-salao-de-festas


# 🎭 Palco

Landing page de um salão de festas **fictício** — inspirado em teatros clássicos, casas de espetáculo e cortinas de veludo. Projeto de demonstração de front-end: HTML, CSS e JavaScript puros em um único arquivo, sem frameworks, sem build step.

![Hero da página Palco](readme_assets/hero.jpg)

## Sobre o projeto

Palco foi feito pra fugir do visual "salão de festas rosa-claro com fonte manuscrita" — a estética aqui é de **cartaz de teatro dos anos 70**: bordô-veludo, dourado antigo, magenta neon como acento de marquise. Toda a linguagem também segue: os tipos de festa são "atos", o roteiro de serviço tem Ato I / II / III, e a reserva vem em formato de bilhete de teatro.

Não existe salão real por trás disso. Nome, endereço, depoimentos e preços são inventados. As fotos usadas são geradas por IA.

## Preview

| Galeria com molduras | Simulador de orçamento |
|---|---|
| ![Galeria](readme_assets/galeria.jpg) | ![Simulador](readme_assets/simulador.jpg) |

<img src="readme_assets/reserva.jpg" alt="Seção de reserva" width="100%">
<img src="readme_assets/mobile.jpg" alt="Versão mobile" width="280">

## Destaques

- **Zero build** — um único arquivo `.html` autocontido, imagens embutidas em base64. Abre direto no navegador ou em qualquer host estático.
- **Cortina de teatro animada no load** — duas metades que se afastam do centro revelando o hero.
- **Simulador de orçamento interativo** — usuário escolhe tipo de festa, número de convidados (slider) e data. Um "programa personalizado" (playbill) é gerado em tempo real com salão sugerido, duração, equipe e preço estimado.
- **Countdown ao vivo** para o próximo sábado — atualiza de segundo em segundo.
- **Galeria com lightbox** de moldura dourada, tipo quadro de museu, com legendas.
- **Spotlight que segue o mouse** no desktop — círculo de luz suave acompanhando o cursor.
- **Reserva em formato de bilhete de teatro**, com perfurações circulares nas laterais.
- **`prefers-reduced-motion` respeitado** — cortina, spotlight e reveals são desativados para quem pediu menos movimento no sistema.
- **Responsivo de verdade** — layout recomposto no mobile, testado em 390px sem overflow.

## Stack

- HTML5 + CSS3 (custom properties, `clamp()`, grid, flexbox)
- JavaScript vanilla, sem dependências externas
- Fontes: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display), [Playfair Display](https://fonts.google.com/specimen/Playfair+Display), [Manrope](https://fonts.google.com/specimen/Manrope) e [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), via Google Fonts

## Como rodar

Não precisa de servidor nem instalação — é um arquivo HTML único.

```bash
git clone https://github.com/CaikRian/palco.git
cd palco
open palco-salao-festas.html   # macOS
# ou apenas arraste o arquivo para o navegador
```

## Estrutura

```
.
├── palco-salao-festas.html   # arquivo final, pronto para abrir/publicar
└── readme_assets/            # imagens usadas neste README
```

## Aviso

Este é um **site de demonstração**. O salão "Palco", seu endereço, cardápio, preços e depoimentos são fictícios. Todas as fotografias exibidas na página foram **geradas por inteligência artificial** e não retratam um estabelecimento, evento ou pessoas reais.

## Autor

Feito por [**@CaikRian**](https://github.com/CaikRian).
