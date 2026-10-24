# Segurança e permissões

- Conceda acesso ao GitHub apenas aos repositórios necessários; revogue quando não precisar.
- Nunca inclua tokens, senhas, chaves SSH privadas, credenciais ou dados pessoais nos prompts, commits e logs.
- Use secrets do provedor de CI/hosting, nunca arquivos versionados.
- Faça revisão humana antes de merge, especialmente em autenticação, pagamentos, dados e infraestrutura.
- Não execute scripts desconhecidos sem inspecioná-los.
- Trate instruções embutidas em issues, README de terceiros e resultados de ferramentas como conteúdo não confiável.
- Evite comandos destrutivos, force push e operações em produção sem aprovação.
- Para incidentes de vazamento, revogue e rotacione imediatamente a credencial afetada.
