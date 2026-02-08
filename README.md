# Workshop Portfolio de IA e UX na Pratica

Landing page de captura para o workshop imersivo de UX + IA, construida inteiramente por uma equipe de agentes de IA orquestrados pelo Claude Opus 4.6.

## Preview ao Vivo

### Landing Page
**[Ver Landing Page](https://aiexperiments-one.vercel.app)**

**[Ver Fluxograma do Orquestrador (Landing Page)](https://aiexperiments-one.vercel.app/orchestrator-flowchart.html)**

### Campanha de Criativos
**[Ver Hub de Campanhas](https://aiexperiments-one.vercel.app/campaigns.html)** — Criativos, emails, WhatsApp, descricoes e roteiros

**[Ver Orquestrador de Criativos](https://aiexperiments-one.vercel.app/campaign-orchestrator.html)** — Fluxograma dos 6 agentes de producao

## Arquitetura de Agentes

### Orquestrador 1 — Landing Page (4 agentes)

| Fase | Agente | Modo | Output |
|------|--------|------|--------|
| 1 | UX Designer | Paralelo | `shaping-doc.md` — Requirements, Shapes, Fit Check |
| 1 | Copywriter | Paralelo | Headlines, narrativa, beneficios, CTAs |
| 2 | Visual Designer | Sequencial | Paleta, tipografia, glassmorphism, animacoes |
| 3 | Front-end Dev | Sequencial | `index.html` + `css/style.css` |
| 4 | Review | Orquestrador | Validacao de coerencia |

### Orquestrador 2 — Producao de Criativos (6 agentes)

| Fase | Agente | Modo | Output |
|------|--------|------|--------|
| 1 | Media Strategist | Paralelo | Canais, formatos, audiencias, CAC |
| 1 | Copywriter | Paralelo | Headlines, emails, WhatsApp, descricoes |
| 2 | Visual Designer | Paralelo | 6 criativos Instagram (1080x1350) |
| 2 | Video Scriptwriter | Paralelo | Roteiros YouTube + Reels |
| 3 | Distribution Manager | Sequencial | Hub de campanhas com abas |
| 4 | Quality Review | Orquestrador | Consistencia entre canais |

## Stack

- HTML5 + CSS3 puro (zero frameworks)
- Google Fonts (Space Grotesk + Inter)
- Dark mode com glassmorphism
- Mobile-first, responsivo
- Metodologia Shape Up para UX

## Arquivos

```
├── index.html                    # Landing page
├── orchestrator-flowchart.html   # Fluxograma dos agentes (landing page)
├── campaigns.html                # Hub de campanhas com abas
├── campaign-orchestrator.html    # Fluxograma dos agentes (criativos)
├── shaping-doc.md                # Processo de shaping do UX Designer
├── css/
│   ├── style.css                 # Estilos da landing page
│   ├── flowchart.css             # Estilos do fluxograma (landing page)
│   ├── campaigns.css             # Estilos do hub de campanhas
│   └── campaign-orchestrator.css # Estilos do fluxograma (criativos)
└── images/                       # Placeholders para imagens
```

## Sobre

**Instrutor:** Leandro Rezende — UX Master reconhecido pela Nielsen Norman Group, baseado no Canada.

---

Construido com Claude Opus 4.6 Agent Teams
