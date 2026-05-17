---
name: case-law-to-content
description: "Transforma acórdãos, ementas, decisões judiciais, notícias jurídicas e teses jurisprudenciais em conteúdo digital para advogados, empresas e público jurídico. Use para criar posts, artigos, newsletters, roteiros, carrosséis e alertas com contexto, limites do precedente, impacto prático e cautela técnica."
license: MIT
metadata:
  version: "1.0.0"
  language: "pt-BR"
---

# Jurisprudência para Conteúdo Digital

## Quando usar

Use esta skill quando o usuário fornecer ou pedir análise de:

- acórdão;
- ementa;
- sentença;
- decisão monocrática;
- notícia de tribunal;
- informativo de jurisprudência;
- tese fixada;
- súmula;
- tema repetitivo ou repercussão geral;
- mudança de entendimento;
- decisão trabalhista, cível, digital, empresarial ou constitucional com potencial de conteúdo.

## Objetivo

Converter material jurisprudencial em conteúdo digital claro, útil e tecnicamente responsável, evitando:

- transformar decisão isolada em regra geral;
- omitir órgão julgador, data ou contexto;
- prometer resultado;
- simplificar excessivamente;
- ignorar divergências;
- confundir precedente vinculante, orientação persuasiva e caso concreto;
- usar decisão como isca de captação.

## Procedimento

1. Identifique o tipo de fonte:
   - decisão isolada;
   - acórdão;
   - notícia institucional;
   - informativo;
   - súmula;
   - tema repetitivo;
   - repercussão geral;
   - precedente qualificado;
   - jurisprudência dominante;
   - tendência ainda incipiente.
2. Extraia os metadados essenciais:
   - tribunal ou órgão;
   - turma, seção, câmara ou órgão julgador;
   - data;
   - número do processo, se fornecido;
   - relator, se fornecido;
   - área do direito;
   - tema central.
3. Separe:
   - fatos do caso;
   - questão jurídica;
   - fundamentos;
   - conclusão;
   - alcance prático;
   - limites da decisão.
4. Classifique o grau de generalização possível:
   - baixo: decisão muito dependente de fatos;
   - médio: decisão relevante, mas sem caráter vinculante;
   - alto: tese, súmula, repetitivo, repercussão geral ou orientação consolidada.
5. Defina o público e canal.
6. Crie o conteúdo com:
   - contexto;
   - tese central;
   - impacto prático;
   - limites;
   - ressalva do caso concreto;
   - CTA informativo.
7. Recomende revisão com `legal-accuracy-review` e `oab-compliance-review` antes de publicação.

## Formato de saída

Entregue:

1. Resumo técnico da decisão.
2. Classificação do precedente.
3. Grau de generalização: baixo, médio ou alto.
4. Riscos de extrapolação.
5. Tese central para conteúdo.
6. Versão sugerida por canal, se solicitado.
7. Ressalvas obrigatórias.
8. Pontos que exigem fonte ou conferência humana.

## Regras de segurança jurídica

- Não invente número de processo, relator, turma, data ou tese.
- Se a fonte não trouxer metadados, marque como "não informado".
- Não use expressões como "agora todos têm direito" ou "o tribunal decidiu que sempre".
- Diferencie decisão isolada de entendimento consolidado.
- Quando a decisão depender dos fatos, destaque isso expressamente.
- Quando houver notícia jornalística ou institucional, recomende consultar o inteiro teor antes de conclusão forte.
- Se houver conflito jurisprudencial conhecido ou provável, indique necessidade de pesquisa adicional.

## Referências internas

Leia `references/classificacao-precedentes.md` para classificar a força da decisão.

Leia `references/modelos-conteudo-jurisprudencia.md` para formatos de post, newsletter, artigo e carrossel.

Leia `references/checklist-extrapolacao.md` para revisar riscos de generalização indevida.
