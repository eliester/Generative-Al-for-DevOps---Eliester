# Revisão Automatizada de Pull Requests IaC

Nome: Eliester De Arruda Alves

## Objetivo

Demonstrar domínio de Prompt Engineering criando três versões evolutivas de um prompt para análise automática de Pull Requests de Infraestrutura como Código.

---

## Estratégia Utilizada

### v1 - Baseline

Primeira versão com instruções simples e abertas.
Objetivo: permitir classificação básica de PRs.

Limitações:
- Respostas inconsistentes
- Formato variável
- Difícil automação

---

### v2 - Structured

Adição de:
- Critérios técnicos explícitos
- Estrutura obrigatória de resposta
- Maior padronização

Resultado:
- Melhor previsibilidade
- Mais adequado para comparação

---

### v3 - Schema + Segurança

Melhorias implementadas:

- Defesa explícita contra Prompt Injection
- Proibição de execução de código
- Ignorar instruções maliciosas no PR
- Saída exclusivamente em JSON estruturado
- Schema fixo e validável

Resultado:
- Alta consistência
- Pronto para integração com CI/CD
- Maior confiabilidade em ambiente corporativo

---

## Conclusão

A evolução demonstra maturidade em engenharia de prompt:

v1 → funcional  
v2 → estruturado  
v3 → seguro, automatizável e resiliente  

A versão 3 apresentou melhores resultados consistentes e maior proteção contra manipulação do modelo.