# Central Operacional 6D / ADL — especificação inicial

**Estado:** protótipo planejado em branch isolada; não representa automação autônoma já instalada.

## Missão
Centralizar o andamento dos projetos ADL Auto, ADL Mídia e Shopee Gestão, mantendo histórico verificável, prioridades, aprovações e próximos passos, com orçamento incremental de R$ 0,00 até autorização explícita.

## Ciclo operacional 6D
1. **Detectar** mudanças nos repositórios e resultados de testes.
2. **Diagnosticar** erros, bloqueios e oportunidades.
3. **Decidir** proposta com prioridade, custo e risco.
4. **Delegar/Desenvolver** somente ações autorizadas, em branch de trabalho.
5. **Demonstrar** evidências: commits, testes, arquivos e URLs.
6. **Documentar** decisões e pendências para retomada.

## Inventário
| Projeto | Repositório | Prioridade atual |
|---|---|---|
| ADL Mídia | israelrodriguesnogueira-ai/ADL-MIDIA | validar exportação e integração de vídeo por IA |
| Shopee Gestão | israelrodriguesnogueira-ai/SHOEEP-GESTAO | verificar estado do painel e integrações |
| ADL Auto | israelrodriguesnogueira-ai/ADL-AUTO- | definir e implementar central de operações |

## Regras de segurança
- Nenhum pagamento, compra, contratação ou publicação em produção sem autorização específica.
- Nunca colocar segredos ou tokens no GitHub ou em páginas públicas.
- Preferir branches e testes antes de alterar main.
- Registrar evidências; não confundir teste sintético com anúncio final.
- Uma autorização genérica de continuidade não substitui aprovações de ações irreversíveis.

## Próximas entregas
- Arquivo de estado estruturado com tarefas e dependências.
- Interface da central com leitura de estado e acompanhamento.
- Testes de consistência do inventário.
- Avaliar integração automatizada com GitHub Actions, com permissões mínimas.
