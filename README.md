# Liberdade em Camadas

Mapa cultural em realidade aumentada do Quilombo Urbano da Liberdade (São Luís – MA).
Projeto do IEMA Pleno São Luís – Cidade Operária: realidade aumentada e educação patrimonial.

- `index.html`: mapa por camadas, fichas dos 8 pontos, maquetes 3D (model-viewer) com botão de RA.
- `ar.html`: modo mapa-marcador (A-Frame 1.3.0 + AR.js 3.4.5), reconhece os marcadores impressos.
- `modelos/`: maquetes .glb (escala reduzida, maior lado = 1 m).
- `marcadores/`: padrões `.patt` do AR.js e imagens dos marcadores.
- `impressao/`: mapa-marcador (A3) e cartões (A4) em PDF. Imprima em 100%.

Site estático: não precisa de build. A câmera exige https.

No ar: https://liberdade-em-camadas.vercel.app
