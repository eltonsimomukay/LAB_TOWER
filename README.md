# LAB TOWER 3D ULTIMATE

Jogo educativo HTML5 responsivo em português, com **30 níveis**, **3 mundos**, **3 chefes**, seis tipos de vidrarias, colisões de corpos rígidos usando **cannon-es**, modelos procedurais em Three.js, sons sintetizados e questões de Química.

## Como jogar
- Arraste sobre a tela para orientar a câmera e a mira.
- Toque em **LANÇAR** (ou espaço) para disparar.
- Toque em **PESADA** (ou E) para armar a próxima esfera especial.
- Derrube todas as vidrarias e responda ao desafio para avançar.
- Os níveis 10, 20 e 30 contêm chefes com resistência adicional.
- Ao completar o nível 30, surge a mensagem secreta **PRECIPITADOS ANALÍTICOS PPT**.

## GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Acesse Settings → Pages → Build and deployment → Deploy from a branch.
4. Selecione `main` e `/(root)` e salve.
5. Aguarde a publicação no endereço `https://USUARIO.github.io/REPOSITORIO/`.

## Dependências e observações
O jogo usa Three.js 0.164.1 e cannon-es 0.20.0 carregados via CDN (jsDelivr). Portanto, é necessária conexão com a internet para carregar as bibliotecas. As vidrarias são modelos 3D procedurais; a física usa corpos rígidos com colisores simplificados, e a quebra de vidro é um efeito visual, não simulação de fratura material. Sons são gerados pela Web Audio API após interação do usuário. A pontuação é local, sem ranking online.
