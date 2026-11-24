# O seu Jarvis â€” degrau 2 de "Do chat ao agente" (ARCKHÉ Learning v7.2)

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo do degrau 2 da formaÃ§Ã£o [Do chat ao agente](https://linnoff88-dev.github.io/ um assistente pessoal com a memÃ³ria e a personalidade que vocÃª definir, usando o [INTELECTO](https://github.com/linnoff88-dev/intelecto) como exemplo. Oito aulas: as sete peÃ§as de um agente, a identidade em quatro arquivos, o bot no Telegram, construir com o Claude Code ou o Codex e provar com testes, memÃ³ria, nuvem ou local, ferramentas e cofre, e uma rotina de verdade com o assistente no ar.

**Abrir o curso:** https://linnoff88-dev.github.io/

**Other languages / Otros idiomas:** [English](https://linnoff88-dev.github.io/ Â· [EspaÃ±ol](https://linnoff88-dev.github.io/

## Como funciona

| Arquivo | O que Ã© |
|---|---|
| `conteudo/pt/curso.json` | nome, vÃ­deos, pÃ¡gina inicial e textos da interface |
| `conteudo/pt/aulas/*.json` | uma aula por arquivo (diagrama, passos, cÃ³digo, simulaÃ§Ã£o, prÃ¡tica, vÃ­deo, quiz, resumo, links) |
| `gerar.py` | monta `index.html` e `aulas/<slug>/index.html` |
| `validar.py` | portÃ£o de qualidade (`--links` confere os links externos) |
| `assets/` | CSS, JS, imagens e legendas |
| `conteudo/en/`, `conteudo/es/` Â· `en/`, `es/` | versÃµes em inglÃªs e espanhol (geradas por `traduzir.py` da skill, cache em `i18n/`) |

```bash
python3 gerar.py && python3 validar.py --links
node ~/.claude/skills/formato-curso-v72/scripts/conferir-tela.cjs .
```

HTML estÃ¡tico, sem build e sem backend. O progresso fica sÃ³ no navegador de quem estuda.

VÃ­deos jÃ¡ publicados: [as 7 peÃ§as](https://linnoff88-dev.github.io/ [instale o seu Jarvis](https://linnoff88-dev.github.io/ e a sÃ©rie [jornada-agentes](https://github.com/linnoff88-dev/jornada-agentes) (release `video-v2.0.0`). ExercÃ­cios originais em `jornada-agentes/exercicios/02-jarvis.md`.

ConteÃºdo aberto e gratuito Â· [ARCKHÉ AI](https://ARCKHÉ AI)

## Mais no ARCKHÉ AI

- [Ficha completa deste curso](https://www.ARCKHÉ AI/cursos/325-do-chat-ao-agente-degrau-2-o-seu-jarvis-com-memoria-no-telegram-intelecto/)
- [Guia: como aprender inteligÃªncia artificial](https://www.ARCKHÉ AI/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.ARCKHÉ AI/cursos/)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>