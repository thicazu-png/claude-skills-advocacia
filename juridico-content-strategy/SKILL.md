---
name: juridico-content-strategy
description: "Planeja estratégia editorial e calendário de conteúdo jurídico digital para advogados. Use quando o usuário quiser criar pautas, séries, funis informativos, calendário para LinkedIn, blog, newsletter, vídeo ou autoridade profissional jurídica."
license: MIT
metadata:
  version: "1.0.0"
  language: "pt-BR"
---

# Estratégia de Conteúdo Jurídico

## Quando usar

Use esta skill quando o usuário quiser:

- Definir linha editorial jurídica.
- Criar calendário de posts, artigos, newsletters ou vídeos.
- Transformar especialidade jurídica em conteúdo educativo.
- Planejar conteúdo para público empresarial, jurídico ou institucional.
- Organizar ideias em pilares, séries e formatos recorrentes.

## Princípios

1. O conteúdo deve ser informativo, educativo e compatível com sobriedade profissional.
2. A estratégia deve evitar promessa de resultado, captação direta, urgência artificial ou linguagem de venda agressiva.
3. O planejamento deve conectar tese jurídica, público-alvo e decisão prática do leitor.
4. Conteúdo jurídico deve deixar claros limites, contexto e necessidade de avaliação do caso concreto.
5. Quando houver dúvida ética, sinalize que o conteúdo deve passar por revisão com a skill `oab-compliance-review`.

## Procedimento

1. Identifique:
   - área jurídica;
   - público-alvo;
   - objetivo do conteúdo;
   - canais;
   - frequência desejada;
   - nível de profundidade;
   - temas proibidos ou sensíveis.
2. Se o usuário não fornecer esses dados, faça suposições razoáveis e destaque-as.
3. Organize a estratégia em pilares editoriais.
4. Para cada pilar, proponha:
   - temas;
   - ângulo prático;
   - formato recomendado;
   - canal ideal;
   - risco jurídico/ético;
   - CTA informativo.
5. Gere um calendário editorial em tabela.
6. Sugira uma rotina de produção semanal.
7. Marque conteúdos que exigem validação jurisprudencial ou revisão ética.

## Estrutura de saída

Entregue, nesta ordem:

1. Diagnóstico de posicionamento.
2. Pilares editoriais.
3. Matriz de temas.
4. Calendário sugerido.
5. CTAs informativos.
6. Alertas de compliance.
7. Próximos passos.

## Linguagem recomendada

- Clara, técnica e acessível.
- Voltada a tomada de decisão empresarial quando o público for empresa.
- Evite jargão excessivo, salvo quando o público for jurídico.
- Evite chamadas como "garanta", "recupere agora", "não perca seus direitos", "consulta grátis" ou equivalentes.

## Referências internas

Leia `references/pilares-editoriais.md` quando precisar estruturar uma linha editorial completa.

Leia `references/matriz-calendario.md` quando precisar montar calendário ou tabela de temas.
