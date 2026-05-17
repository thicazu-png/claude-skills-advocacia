---
name: legal-accuracy-review
description: "Revisa precisão jurídica, coerência, fontes, limites de tese e riscos de alucinação em conteúdo jurídico. Use para checar posts, artigos, pareceres curtos, newsletters, roteiros e análises antes de publicação ou envio."
license: MIT
metadata:
  version: "1.0.0"
  language: "pt-BR"
---

# Revisão de Precisão Jurídica

## Quando usar

Use esta skill quando precisar revisar:

- Conteúdo jurídico produzido com IA.
- Texto sobre legislação, jurisprudência, doutrina ou regulação.
- Artigo, post, newsletter ou roteiro técnico.
- Síntese de decisão judicial.
- Explicação de risco jurídico.
- Checklist jurídico preventivo.

## Objetivo

Identificar e corrigir:

- afirmações sem fonte;
- extrapolação de precedente;
- confusão entre lei, jurisprudência e opinião;
- omissão de ressalvas;
- generalizações indevidas;
- termos técnicos imprecisos;
- risco de alucinação;
- inconsistências internas.

## Procedimento

1. Identifique a tese central do texto.
2. Separe afirmações jurídicas verificáveis de opinião, estratégia ou comentário.
3. Para cada afirmação jurídica, indique:
   - fonte necessária;
   - grau de segurança;
   - ressalva aplicável;
   - risco de extrapolação.
4. Verifique se decisões judiciais foram tratadas com limite adequado.
5. Revise conceitos técnicos e terminologia.
6. Sugira reescrita para maior precisão.
7. Se faltar fonte, marque como "fonte necessária" em vez de inventar.

## Formato de saída

Entregue:

1. Tese central identificada.
2. Diagnóstico de confiabilidade: alto, médio ou baixo.
3. Tabela de revisão:
   - afirmação;
   - problema;
   - risco;
   - ajuste recomendado.
4. Pontos que exigem fonte.
5. Pontos que exigem revisão humana.
6. Versão revisada, se possível.

## Regras de segurança

- Não invente artigos, precedentes, números de processos ou citações.
- Se uma informação não puder ser verificada no material fornecido, diga que precisa de fonte.
- Diferencie "há entendimento", "há precedentes", "a jurisprudência é pacífica" e "a lei prevê".
- Evite transformar decisão isolada em regra geral.
- Inclua ressalva de caso concreto quando necessário.

## Referências internas

Leia `references/checklist-precisao.md` para classificar risco e confiabilidade.

Leia `references/modelo-revisao.md` para aplicar a tabela padrão.
