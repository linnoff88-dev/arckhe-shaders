# Shaders â€” efeitos WebGPU para sites (espelho + guia INEMA)

[![Sites com Shaders](guia/assets/banner.jpg)](https://inematds.github.io/shaders/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

Shaders Ã© uma biblioteca gratuita e de cÃ³digo aberto (licenÃ§a MIT) com mais de 200 efeitos visuais para pÃ¡ginas web. Ela serve para quem faz sites, landing pages e apps e quer um fundo animado, um brilho ou uma distorÃ§Ã£o sem escrever cÃ³digo de placa de vÃ­deo. Cada efeito Ã© um componente: vocÃª empilha camadas e a placa de vÃ­deo do visitante desenha tudo em tempo real, pela tecnologia WebGPU. Para usar, basta instalar o pacote `shaders` (React, Vue, Svelte, Solid ou JavaScript puro) e abrir num navegador com WebGPU.

## ðŸ“– Guia de uso

Guia completo (demo ao vivo + passo a passo + cuidados): **https://inematds.github.io/shaders/guia/**

## InÃ­cio rÃ¡pido

```bash
npm install shaders
```

```jsx
import { Shader, LinearGradient, CursorTrail } from 'shaders/react'

<Shader className="w-full h-64" disableTelemetry>
  <LinearGradient colorA="#0c0c10" colorB="#E2A23B" />
  <CursorTrail />
</Shader>
```

## Antes de usar

- Nem todo navegador tem WebGPU: deixe um fundo estÃ¡tico no lugar.
- A telemetria vem ligada (cerca de 5% das visitas mandam dados de desempenho para o shaders.com): use `disableTelemetry`.
- Editor visual, CLI conectada e MCP pedem conta no shaders.com; presets prontos e seÃ§Ãµes de site sÃ£o do plano Pro.

## CrÃ©ditos

Este repositÃ³rio Ã© um **espelho** de [shader-effects-inc/shaders](https://github.com/shader-effects-inc/shaders) (Â© Shader Effects, Inc., licenÃ§a MIT), com o guia do INEMA na pasta `guia/`. O README original estÃ¡ em [README.upstream.md](README.upstream.md). Os workflows de release e teste do autor foram removidos do espelho; ficou sÃ³ o deploy do GitHub Pages.

---

[INEMA.CLUB](https://inema.club)

---

Projeto adaptado da comunidade INEMA TDS · Marca **Arckhé**

Feito pelo **[ARCKHÉ.AI](https://linnoff88-dev.github.io/arckhe-ai)**.