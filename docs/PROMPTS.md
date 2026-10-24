# Prompts prontos

## 1. Explorar um projeto
"Analise o repositório [OWNER/REPO]. Leia README.md, AGENTS.md e arquivos relevantes. Explique arquitetura, tecnologias, como executar e riscos. Não altere arquivos."

## 2. Criar funcionalidade
"No repositório [OWNER/REPO], implemente [FUNCIONALIDADE]. Critérios de aceite: [CRITÉRIOS]. Leia AGENTS.md; preserve código existente e trabalho concorrente. Prefira branch + PR. Mostre diff, testes realmente executados, commit e pendências."

## 3. Corrigir bug
"Investigue [ERRO] em [OWNER/REPO]. Reproduza quando houver runtime autorizado, identifique causa raiz, implemente correção mínima e teste de regressão. Se não puder reproduzir, registre essa limitação."

## 4. Revisar código
"Revise o PR [LINK]. Procure bugs, regressões, falhas de segurança, problemas de manutenção e testes ausentes. Priorize achados com arquivo/linha. Não altere nada."

## 5. Continuar trabalho
"Recupere o estado atual de [OWNER/REPO] e o PR [NÚMERO]. Leia AGENTS.md, verifique commits novos e continue somente as pendências. Não reimplemente tarefas concluídas."
