# CLAUDE.md — Orientações para Claude

Leia primeiro `AGENTS.md`: ele contém as regras compartilhadas deste projeto e prevalece sobre recomendações específicas deste arquivo quando houver divergência.

## Usando Claude Code
- Abra a pasta do repositório e leia as instruções antes de editar.
- Inspecione `git status`, branch e diff; preserve alterações locais e trabalho concorrente.
- Planeje brevemente antes de mudanças com múltiplos arquivos.
- Utilize as ferramentas reais disponíveis para editar, executar testes e conferir resultados.
- Não confunda Claude Chat (conversa e análise) com Claude Code (ferramentas de desenvolvimento quando habilitadas).
- Solicite aprovação antes de comandos destrutivos, mudanças de infraestrutura ou operações de produção.
- Prefira PR com diff revisável; não faça push forçado.
- Ao finalizar, reporte comandos executados, resultados, arquivos e commit/PR; identifique SKIP/BLOCKED.

## Prompt inicial
"Leia AGENTS.md, CLAUDE.md e README.md. Inspecione o repositório e proponha o menor plano para [TAREFA]. Execute somente o que suas ferramentas e permissões permitirem; valide e reporte evidências."
