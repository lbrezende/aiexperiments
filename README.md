# Workshop Portfolio de IA e UX na Pratica

Landing page de captura para o workshop imersivo de UX + IA, construida inteiramente por uma equipe de agentes de IA orquestrados pelo Claude Opus 4.6.

## Preview ao Vivo

**[Ver Landing Page](https://aiexperiments-one.vercel.app)**

**[Ver Fluxograma do Orquestrador](https://aiexperiments-one.vercel.app/orchestrator-flowchart.html)**

## Arquitetura de Agentes

Este projeto foi construido por 4 agentes especializados, gerenciados por um orquestrador (Claude Opus 4.6):

| Fase | Agente | Modo | Output |
|------|--------|------|--------|
| 1 | UX Designer | Paralelo | `shaping-doc.md` — Requirements, Shapes, Fit Check |
| 1 | Copywriter | Paralelo | Headlines, narrativa, beneficios, CTAs |
| 2 | Visual Designer | Sequencial | Paleta, tipografia, glassmorphism, animacoes |
| 3 | Front-end Dev | Sequencial | `index.html` + `css/style.css` |
| 4 | Review | Orquestrador | Validacao de coerencia |

## Stack

- HTML5 + CSS3 puro (zero frameworks)
- Google Fonts (Space Grotesk + Inter)
- Dark mode com glassmorphism
- Mobile-first, responsivo
- Metodologia Shape Up para UX

## Arquivos

```
├── index.html                  # Landing page
├── orchestrator-flowchart.html # Fluxograma visual dos agentes
├── shaping-doc.md              # Processo de shaping do UX Designer
├── css/
│   ├── style.css               # Estilos da landing page
│   └── flowchart.css           # Estilos do fluxograma
└── images/                     # Placeholders para imagens
```

## Sobre

**Instrutor:** Leandro Rezende — UX Master reconhecido pela Nielsen Norman Group, baseado no Canada.

---

Construido com Claude Opus 4.6 Agent Teams
