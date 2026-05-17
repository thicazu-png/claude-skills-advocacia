# Instalação rápida

Este repositório contém 10 Claude Skills em português para advocacia, conteúdo jurídico, revisão contratual, Visual Law, jurisprudência e gestão jurídica com IA.

## Baixar o pacote completo

O pacote completo está em:

```text
dist/claude-skills-advocacia-mvp-10-skills.zip
```

Baixe o ZIP, descompacte no seu computador e importe as skills individualmente no Claude.

## Importar no Claude

1. Descompacte o arquivo ZIP.
2. Abra o Claude.
3. Acesse a área de Skills.
4. Importe uma pasta de skill por vez.
5. Cada pasta deve conter o arquivo `SKILL.md`.
6. Se a skill tiver `references/` ou `assets/`, mantenha essas pastas junto com o `SKILL.md`.

## Skills incluídas

```text
business-tech-contract-review
case-law-to-content
digital-law-lgpd-ai-content
juridico-content-strategy
labor-law-business-content
legal-accuracy-review
legal-ops-ai-management
multichannel-repurposing
oab-compliance-review
visual-law-legal-design
```

## Teste rápido

Depois de importar, teste com um prompt simples:

```text
Use a skill juridico-content-strategy para criar um calendário editorial de 4 semanas sobre direito do trabalho empresarial para LinkedIn, com foco em RH e empresas.
```

Outro teste:

```text
Use a skill oab-compliance-review para revisar este post antes da publicação:

"Empresas que não regularizarem o banco de horas podem perder muito dinheiro. Fale comigo agora para evitar problemas trabalhistas."
```

## Fluxo recomendado para conteúdo jurídico

1. `juridico-content-strategy`
2. `labor-law-business-content` ou `digital-law-lgpd-ai-content`
3. `legal-accuracy-review`
4. `oab-compliance-review`
5. `multichannel-repurposing`
6. `visual-law-legal-design`

## Fluxo recomendado para contratos

1. `business-tech-contract-review`
2. `legal-accuracy-review`, se houver tese jurídica relevante.
3. `visual-law-legal-design`, se quiser matriz, quadro ou one-pager executivo.

## Fluxo recomendado para jurisprudência

1. `case-law-to-content`
2. `legal-accuracy-review`
3. `oab-compliance-review`
4. `multichannel-repurposing`
5. `visual-law-legal-design`

## Guia completo

Consulte:

```text
docs/guia-instalacao-uso.md
```

## Observação profissional

As skills apoiam o trabalho jurídico, mas não substituem revisão técnica, responsabilidade profissional, sigilo, ética, análise individualizada ou validação humana.
