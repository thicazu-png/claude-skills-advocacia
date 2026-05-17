---
name: multichannel-repurposing
description: "Adapta conteúdo jurídico-base para múltiplos canais digitais, incluindo LinkedIn, newsletter, blog, roteiro de vídeo curto e carrossel. Use quando o usuário quiser reaproveitar uma tese jurídica ou artigo em formatos diferentes com linguagem adequada a cada canal."
license: MIT
metadata:
  version: "1.0.0"
  language: "pt-BR"
---

# Reaproveitamento Multicanal de Conteúdo Jurídico

## Quando usar

Use esta skill quando o usuário tiver:

- artigo jurídico e quiser transformar em posts;
- decisão judicial e quiser criar conteúdo educativo;
- tese de palestra e quiser criar newsletter;
- post longo e quiser criar carrossel;
- conteúdo técnico e quiser adaptar para público empresarial;
- ideia única e quiser gerar uma sequência por canal.

## Princípios

1. Preserve precisão jurídica e ressalvas necessárias.
2. Ajuste profundidade e tom ao canal.
3. Evite clickbait jurídico, promessa de resultado e CTA agressivo.
4. Mantenha linguagem sóbria, clara e autoral.
5. Não simplifique a ponto de distorcer a tese.

## Procedimento

1. Identifique tese central, público e objetivo.
2. Extraia 3 a 5 ideias principais.
3. Defina os canais desejados.
4. Para cada canal, adapte:
   - gancho;
   - estrutura;
   - profundidade;
   - CTA;
   - ressalvas.
5. Se o conteúdo tiver risco jurídico ou ético, recomende revisão com `legal-accuracy-review` e `oab-compliance-review`.

## Formatos padrão

Use os templates em `assets/`:

- `linkedin-post.md`
- `newsletter.md`
- `blog-outline.md`
- `video-curto.md`
- `carrossel.md`

## Formato de saída

Entregue:

1. Tese central.
2. Ideias reaproveitáveis.
3. Versões por canal.
4. CTAs informativos.
5. Pontos que exigem revisão jurídica ou ética.

## Regras de canal

### LinkedIn

Use gancho forte, mas não sensacionalista. Priorize clareza, exemplo prático e conclusão útil.

### Newsletter

Use tom mais analítico. Inclua contexto, consequência prática e próximos passos.

### Blog

Use estrutura SEO-friendly, subtítulos claros e desenvolvimento mais completo.

### Vídeo curto

Use uma tese por vídeo. Frases curtas. Sem prometer solução individual.

### Carrossel

Use uma ideia por lâmina, com progressão lógica e CTA informativo.
