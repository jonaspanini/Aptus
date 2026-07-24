# Manual de Arquitetura do Aptus

Versão: 1.0.0

## Princípios
- PA-001 Offline First
- PA-002 Persistência Local
- PA-003 Sincronização Assíncrona
- PA-004 Nunca Perder Dados
- PA-005 Responsabilidade Única
- PA-006 Servidor como Réplica
- PA-007 Resposta Imediata
- PA-008 Arquitetura Evolutiva

## Fluxo
UI → Use Cases → Repository → Banco Local → Queue → Sync Engine → Servidor

## Critérios
- Funciona offline
- Persiste localmente
- Sincroniza posteriormente
- Recupera após reinício
- Não perde dados
