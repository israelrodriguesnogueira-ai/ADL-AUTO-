# Revisão operacional — 10/11/2026, 17h53 (Brasília)

## Evidências verificadas diretamente na integração GitHub

| Projeto | Estado confirmado | Limitação |
| --- | --- | --- |
| ADL Mídia | O arquivo `estudio-shopee.html` existe na branch `feature/video-ai-integration-prep`; exporta montagem de três fotografias com zoom suave | Não gera giro cinematográfico por IA nem garante vídeo final com vestido real |
| ADL Mídia / Actions | Execução 42892976326: job `exportacao` concluído com sucesso; Playwright, ffprobe e upload passaram. Artefato `video-teste-shopee`, id 13799072167, não expirado | O vídeo usa imagens de teste sintéticas, não fotos do produto |
| ADL Auto | `central-6d.html` e `data/estado-operacional.json` presentes na branch `feature/central-operacional-6d`; carregamento relativo de JSON implementado | Sem comprovação de renderização em navegador ou publicação em produção |
| ADL Auto / Actions | `.github/workflows/validar-central-6d.yml` está presente e valida JSON, inventário e regras de custo zero | Consulta de runs por commit não retornou execuções; **não** declarar teste aprovado |
| Shopee Gestão | `README.md` da branch main contém apenas título e palavra "Gestão" | Não há evidência de interface funcional ou integração da loja |

## Branches e revisões confirmadas
- ADL Auto: `feature/central-operacional-6d`; PR em rascunho https://github.com/israelrodriguesnogueira-ai/ADL-AUTO-/pull/1 (não mesclado)
- ADL Mídia: `feature/video-ai-integration-prep`; PR em rascunho https://github.com/israelrodriguesnogueira-ai/ADL-MIDIA/pull/7 (não mesclado)
- Shopee Gestão: `main` com README inicial confirmado. Outras branches não inventariadas nesta revisão.

## Links de evidência
- Teste de exportação aprovado: https://github.com/israelrodriguesnogueira-ai/ADL-MIDIA/actions/runs/42892976326
- Artefato: https://github.com/israelrodriguesnogueira-ai/ADL-MIDIA/actions/runs/42892976326/artifacts/13799072167
- Painel 6D (código): https://github.com/israelrodriguesnogueira-ai/ADL-AUTO-/blob/feature/central-operacional-6d/central-6d.html
- Estúdio Shopee (código): https://github.com/israelrodriguesnogueira-ai/ADL-MIDIA/blob/feature/video-ai-integration-prep/estudio-shopee.html

## Pendências prioritárias
1. Validar painel 6D no navegador e obter execução comprovada do workflow; PR está em rascunho.
2. Verificar acesso às fotos originais do vestido, gerar movimento realista sem deformações e incorporar trilha com direitos de uso.
3. Reproduzir e inspecionar arquivo final de 15 s, vertical, no celular; conferir costas fechadas com zíper, alças finas, amarração e fenda lateral frontal.
4. Implementar interface e integração Shopee Gestão, e obter aprovação expressa para publicar na loja.

**Restrições respeitadas:** nenhum serviço pago contratado, nenhum merge na main, nenhuma publicação na loja. Este relatório não constitui certificação de funcionamento em produção.
