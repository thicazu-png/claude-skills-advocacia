# Claude Skills Advocacia

Pacote de **Agent Skills para Claude** em português, voltado a advogados, escritórios e profissionais jurídicos que desejam usar IA generativa com método, revisão técnica, governança e cuidado ético.

O pacote foi estruturado para apoiar produção de conteúdo jurídico, revisão de precisão, compliance de publicidade profissional, Visual Law, análise de jurisprudência, revisão contratual empresarial/tecnológica e gestão interna de escritório jurídico com IA.

## O que há neste repositório

| Skill | Finalidade |
| --- | --- |
| `juridico-content-strategy` | Estratégia editorial, calendário, pautas e pilares de conteúdo jurídico. |
| `oab-compliance-review` | Revisão de sobriedade, publicidade jurídica, mercantilização e captação indevida. |
| `legal-accuracy-review` | Checagem de precisão jurídica, fontes, ressalvas e extrapolações. |
| `multichannel-repurposing` | Adaptação de conteúdo para LinkedIn, newsletter, blog, vídeo curto e carrossel. |
| `labor-law-business-content` | Conteúdo trabalhista empresarial para empresas, RH, compliance e jurídico interno. |
| `digital-law-lgpd-ai-content` | Conteúdo sobre direito digital, LGPD, IA, contratos de tecnologia e governança. |
| `case-law-to-content` | Transformação de decisões, acórdãos, ementas e notícias jurídicas em conteúdo. |
| `visual-law-legal-design` | Visual Law, quadros, checklists visuais, fluxos, mapas e one-pagers. |
| `business-tech-contract-review` | Revisão de contratos empresariais e tecnológicos, SaaS, NDA, DPA, PI e SLA. |
| `legal-ops-ai-management` | Gestão de escritório jurídico com IA, triagem, playbooks, QA e base de conhecimento. |

## Como instalar no Claude

### Instalação por skill

1. Baixe este repositório em ZIP ou clone o projeto.
2. Escolha a pasta da skill desejada.
3. No Claude, acesse a área de Skills.
4. Importe a pasta inteira da skill, mantendo:
   - `SKILL.md`;
   - `references/`, quando existir;
   - `assets/`, quando existir.
5. Teste a skill com um prompt simples.

### Instalação do pacote completo

Você também pode baixar o pacote completo em:

```text
dist/claude-skills-advocacia-mvp-10-skills.zip
```

Depois, descompacte e importe as skills individualmente no Claude.

## Guia completo

O passo a passo detalhado está em:

```text
docs/guia-instalacao-uso.md
```

O guia inclui:

- instruções de instalação;
- prompts de teste para cada skill;
- fluxos práticos de uso;
- prompts mestres;
- boas práticas de revisão jurídica e compliance;
- checklist final de instalação.

## Fluxos recomendados

### Conteúdo jurídico

1. `juridico-content-strategy`
2. `labor-law-business-content` ou `digital-law-lgpd-ai-content`
3. `legal-accuracy-review`
4. `oab-compliance-review`
5. `multichannel-repurposing`
6. `visual-law-legal-design`

### Jurisprudência para conteúdo

1. `case-law-to-content`
2. `legal-accuracy-review`
3. `oab-compliance-review`
4. `multichannel-repurposing`
5. `visual-law-legal-design`

### Revisão contratual

1. `business-tech-contract-review`
2. `legal-accuracy-review`, se houver tese jurídica relevante
3. `visual-law-legal-design`, se quiser matriz ou one-pager executivo

### Gestão interna

1. `legal-ops-ai-management`
2. `business-tech-contract-review`, quando a rotina envolver contratos
3. `oab-compliance-review`, quando a rotina envolver publicação externa

## Observações importantes

Este pacote não substitui revisão profissional, responsabilidade técnica, sigilo, ética ou análise individualizada. As skills foram desenhadas para apoiar o método de trabalho jurídico, não para automatizar decisões profissionais sensíveis sem supervisão humana.

Antes de usar documentos reais, avalie confidencialidade, dados pessoais, dados sensíveis, segredo profissional, política de segurança e ambiente em que a IA será utilizada.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE`.
