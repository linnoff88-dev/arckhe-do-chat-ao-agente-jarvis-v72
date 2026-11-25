# O seu Jarvis ê¢â¬â degrau 2 de "Do chat ao agente" (ARCKHê Learning v7.2)

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo do degrau 2 da formaêÂ§êÂ£o [Do chat ao agente](https://linnoff88-dev.github.io/ um assistente pessoal com a memêÂ³ria e a personalidade que vocêÂª definir, usando o [INTELECTO](https://github.com/linnoff88-dev/intelecto) como exemplo. Oito aulas: as sete peêÂ§as de um agente, a identidade em quatro arquivos, o bot no Telegram, construir com o Claude Code ou o Codex e provar com testes, memêÂ³ria, nuvem ou local, ferramentas e cofre, e uma rotina de verdade com o assistente no ar.

**Abrir o curso:** https://linnoff88-dev.github.io/

**Other languages / Otros idiomas:** [English](https://linnoff88-dev.github.io/ êÂ· [EspaêÂ±ol](https://linnoff88-dev.github.io/

## Como funciona

| Arquivo | O que êÂ© |
|---|---|
| `conteudo/pt/curso.json` | nome, vêÂ­deos, pêÂ¡gina inicial e textos da interface |
| `conteudo/pt/aulas/*.json` | uma aula por arquivo (diagrama, passos, cêÂ³digo, simulaêÂ§êÂ£o, prêÂ¡tica, vêÂ­deo, quiz, resumo, links) |
| `gerar.py` | monta `index.html` e `aulas/<slug>/index.html` |
| `validar.py` | portêÂ£o de qualidade (`--links` confere os links externos) |
| `assets/` | CSS, JS, imagens e legendas |
| `conteudo/en/`, `conteudo/es/` êÂ· `en/`, `es/` | versêÂµes em inglêÂªs e espanhol (geradas por `traduzir.py` da skill, cache em `i18n/`) |

```bash
python3 gerar.py && python3 validar.py --links
node ~/.claude/skills/formato-curso-v72/scripts/conferir-tela.cjs .
```

HTML estêÂ¡tico, sem build e sem backend. O progresso fica sêÂ³ no navegador de quem estuda.

VêÂ­deos jêÂ¡ publicados: [as 7 peêÂ§as](https://linnoff88-dev.github.io/ [instale o seu Jarvis](https://linnoff88-dev.github.io/ e a sêÂ©rie [jornada-agentes](https://github.com/linnoff88-dev/jornada-agentes) (release `video-v2.0.0`). ExercêÂ­cios originais em `jornada-agentes/exercicios/02-jarvis.md`.

ConteêÂºdo aberto e gratuito êÂ· [ARCKHê AI](https://ARCKHê AI)

## Mais no ARCKHê AI

- [Ficha completa deste curso](https://www.ARCKHê AI/cursos/325-do-chat-ao-agente-degrau-2-o-seu-jarvis-com-memoria-no-telegram-intelecto/)
- [Guia: como aprender inteligêÂªncia artificial](https://www.ARCKHê AI/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.ARCKHê AI/cursos/)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>