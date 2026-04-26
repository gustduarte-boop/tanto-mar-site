# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

**Instituto Tanto Mar** — site de presença web de uma ONG brasileira dedicada à restauração ecológica de recifes de coral, sediada em Corumbau, Bahia. Fundada em março de 2025, 11 fundadores.

**GitHub:** https://github.com/gustduarte-boop/tanto-mar-site  
**Stack:** ainda a definir — repo serve atualmente como repositório de assets e conteúdo para o Claude Design (ferramenta de design da Anthropic).

## Estrutura do repo

```
assets/
  photos/
    aerial/      — frames de drone curados (recife, sandbar, pôr do sol, ecossistema)
    fieldwork/   — mergulhadores trabalhando, pesquisadores no barco
    reefs/       — corais, peixes, miléporas (incluindo miléporas mortas/branqueadas)
  videos/
    hero-loop-reef-aerial.mp4         — 12s, drone, dois barcos sobre recife
    hero-loop-underwater-corumbau.mp4 — 12s, GoPro subaquático, efeito Snell's window
    a-ultima-millepora-viva-720p.mov  — 46s, vídeo do problema (miléporas mortas, 2022)
  maps/          — imagens de satélite Sentinel dos recifes
brand/
  logo/          — logo oficial hi-res (extraído do estatuto 600dpi) + README com cores
  typography/    — fonte Jost (variable font + 6 pesos estáticos)
  colors.md      — paleta: azul #29ABE2, verde #39B54A/#006837, cinza #58595B
  typography.md  — Jost é o clone open-source da Futura, idêntico ao wordmark
content/
  about.md       — missão, por que Tanto Mar, visão, ambições (EN)
  projects.md    — 4 áreas de intervenção
  team.md        — 11 fundadores
  contact.md     — endereço Corumbau + telefone
  data-and-stats.md — dados verificados dos papers científicos (usar estes, não inventar)
photos/          — 19 fotos GoPro subaquáticas adicionadas pelo usuário
references/
  duarte-et-al-2020-heatwaves-corumbau-reefs.pdf  — paper fundador (Gustavo 1º autor)
  teixeira-et-al-2019-bleaching-abrolhos.pdf       — contexto regional
```

## Dados verificados (não substituir por placeholders)

- **~86% mortalidade** de Millepora alcicornis em Corumbau (2019) — Duarte et al. 2020
- **Primeira mortalidade em massa** registrada nos recifes do Atlântico Sul
- **DHW 19.65** — recorde histórico de estresse térmico (maio 2019)
- **~50 km²** — Complexo Itacolomis dentro da RESEX Corumbau
- **11 fundadores**, fundada em 10/03/2025, Prado/BA
- **Corais em recuperação** desde 2019 — narrativa: colapso → recuperação → proteção futura

## Brand

- **Logo:** punho direito erguido + ondas, degradê azul→verde. Ver `brand/logo/README.md` para distinguir da versão antiga (posição do polegar diferente).
- **Tipografia:** Jost (clone da Futura, open-source) — idêntica ao wordmark "TANTO MAR"
- **Wordmark no footer:** branco puro (não usar gradiente no wordmark)
- **CNPJ:** manter como placeholder até confirmar registro finalizado

## Regras de curadoria de fotos

Fotos com **color flag do macOS** = curadas pelo usuário = podem ir pro repo.  
Apenas fotos **de Corumbau** (não misturar outros locais).  
Foco em: mergulho de trabalho/científico, corais, recife, campo — não lazer.
