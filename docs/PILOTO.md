# Aptus - Registro do Piloto

Este documento registra todos os problemas, melhorias e validações encontradas durante o piloto da Aptus.

## Objetivo
Registrar de forma organizada os achados para que as correções sejam priorizadas antes da versão comercial.

## Legenda
- 🟥 Bug crítico
- 🟨 Melhoria
- 🟦 Evolução
- 🟩 Ideia futura

## Registro de Ocorrências

| ID | Tipo | Data | Descrição | Status | Observação |
|----|------|------|-----------|--------|------------|
| P-001 | 🟥 Bug | 17/07/2026 | Cadastro de instrutor grava o registro na tabela `instrutores`, mas falha na criação do usuário/profile. Revisar fluxo de autenticação via Edge Function e Service Role. | Em correção | Confirmado em testes. |
| P-002 | 🟥 Bug | 17/07/2026 | Erro ao salvar sessão: `operator does not exist: text = categoria_cnh`. Padronizar o tipo de dados da categoria CNH em todas as tabelas e consultas. | Em correção | O erro ocorre no encerramento da sessão. |

## Critérios para Liberação do Piloto

- Login funcionando
- Cadastro de instrutores funcionando
- Criação de acesso funcionando
- Cadastro de alunos funcionando
- Início de sessão funcionando
- Encerramento de sessão funcionando
- Assinatura salva corretamente
- Histórico atualizado
- Dashboard atualizado

Somente após todos os itens acima estarem validados o piloto deverá ser ampliado para todos os instrutores da Autoescola Rainha do Vale.