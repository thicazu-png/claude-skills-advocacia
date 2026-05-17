# Guia de instalação e uso do pacote Claude Skills Advocacia

## Visão geral

Este guia explica como instalar, testar e usar o pacote **Claude Skills Advocacia MVP**, composto por 10 skills em português para advocacia empresarial, direito do trabalho, direito digital, LGPD, IA, conteúdo jurídico, Visual Law, jurisprudência, revisão contratual e gestão de escritório jurídico com IA.

O pacote foi criado para funcionar como uma esteira de trabalho. A ideia não é usar todas as skills ao mesmo tempo, mas acionar a skill adequada conforme a tarefa: planejar, produzir, revisar, adaptar, diagramar, analisar contrato, transformar jurisprudência em conteúdo ou organizar rotinas internas.

## Conteúdo do pacote

| Skill | Finalidade principal | Quando usar |
| --- | --- | --- |
| `juridico-content-strategy` | Estratégia editorial jurídica | Calendário, pautas, pilares, linha editorial |
| `oab-compliance-review` | Revisão ética e publicidade jurídica | Antes de publicar posts, artigos, newsletters, vídeos ou CTAs |
| `legal-accuracy-review` | Precisão jurídica | Revisar fontes, teses, riscos de alucinação e extrapolação |
| `multichannel-repurposing` | Reaproveitamento multicanal | Transformar texto-base em LinkedIn, newsletter, blog, vídeo e carrossel |
| `labor-law-business-content` | Conteúdo trabalhista empresarial | Criar conteúdo para empresas, RH, compliance e jurídico interno |
| `digital-law-lgpd-ai-content` | Conteúdo de direito digital, LGPD e IA | Criar conteúdo sobre dados, IA, tecnologia, contratos e inovação |
| `case-law-to-content` | Jurisprudência para conteúdo | Transformar decisões, acórdãos e notícias jurídicas em conteúdo |
| `visual-law-legal-design` | Visual Law e Legal Design | Criar quadros, checklists, fluxos, mapas e carrosséis |
| `business-tech-contract-review` | Revisão contratual empresarial e tecnológica | Analisar SaaS, NDA, DPA, PI, responsabilidade, SLA e rescisão |
| `legal-ops-ai-management` | Gestão jurídica com IA | Criar playbooks, triagem, governança, QA e rotinas internas |

## Como instalar no Claude

### Opção recomendada: importar cada skill separadamente

1. Baixe o arquivo ZIP do pacote.
2. Descompacte o arquivo no seu computador.
3. Você verá uma pasta chamada `claude-skills-advocacia-mvp`.
4. Dentro dela, cada skill está em uma pasta própria, por exemplo:
   - `juridico-content-strategy`
   - `oab-compliance-review`
   - `legal-accuracy-review`
5. No Claude, acesse a área de **Skills**.
6. Importe cada pasta de skill separadamente, mantendo o arquivo `SKILL.md` e suas subpastas `references/` ou `assets/`.
7. Depois de importar, teste cada skill com um prompt curto.

### Opção alternativa: usar como biblioteca local

Se você não quiser importar imediatamente, pode manter o pacote como uma biblioteca de referência. Nesse caso, copie o conteúdo do `SKILL.md` da skill desejada para o Claude quando quiser executar uma tarefa específica. Essa opção é menos prática, mas útil para testar antes da instalação definitiva.

## Como testar cada skill

### Teste da skill `juridico-content-strategy`

Use este prompt:

```text
Use a skill juridico-content-strategy para criar um calendário editorial de 4 semanas sobre direito do trabalho empresarial para LinkedIn, com foco em RH e empresas.
```

Resultado esperado:

- pilares editoriais;
- temas por semana;
- público-alvo;
- canal;
- formato;
- CTA informativo;
- alertas de compliance.

### Teste da skill `oab-compliance-review`

Use este prompt:

```text
Use a skill oab-compliance-review para revisar este post antes da publicação:

"Empresas que não regularizarem o banco de horas podem perder muito dinheiro. Fale comigo agora para evitar problemas trabalhistas."
```

Resultado esperado:

- classificação de risco;
- identificação de linguagem comercial ou alarmista;
- sugestão de reescrita sóbria;
- versão revisada.

### Teste da skill `legal-accuracy-review`

Use este prompt:

```text
Use a skill legal-accuracy-review para revisar a precisão jurídica deste texto:

"Toda pejotização é ilegal e sempre gera vínculo de emprego."
```

Resultado esperado:

- identificação de generalização indevida;
- explicação sobre necessidade de análise fática;
- recomendação de linguagem mais precisa;
- pontos que exigem fonte.

### Teste da skill `multichannel-repurposing`

Use este prompt:

```text
Use a skill multichannel-repurposing para transformar este texto-base em post de LinkedIn, newsletter curta e roteiro de vídeo:

"Empresas devem revisar suas políticas de uso de IA generativa para evitar exposição de dados pessoais, informações confidenciais e outputs sem revisão humana."
```

Resultado esperado:

- tese central;
- versões por canal;
- CTA informativo;
- ressalvas.

### Teste da skill `labor-law-business-content`

Use este prompt:

```text
Use a skill labor-law-business-content para criar um post de LinkedIn para empresas sobre os riscos de mensagens de trabalho fora do expediente.
```

Resultado esperado:

- gancho técnico;
- impacto para empresas;
- pontos de atenção;
- boas práticas;
- ressalva sobre caso concreto.

### Teste da skill `digital-law-lgpd-ai-content`

Use este prompt:

```text
Use a skill digital-law-lgpd-ai-content para criar um artigo curto sobre política interna de IA generativa em empresas.
```

Resultado esperado:

- contexto tecnológico;
- riscos jurídicos;
- checklist de governança;
- recomendações preventivas;
- linguagem acessível.

### Teste da skill `case-law-to-content`

Use este prompt:

```text
Use a skill case-law-to-content para transformar esta notícia de decisão em post educativo, sem extrapolar o precedente:

[cole aqui a notícia, ementa ou resumo da decisão]
```

Resultado esperado:

- resumo técnico;
- classificação do precedente;
- grau de generalização;
- riscos de extrapolação;
- versão para conteúdo.

### Teste da skill `visual-law-legal-design`

Use este prompt:

```text
Use a skill visual-law-legal-design para transformar este tema em um carrossel de 8 lâminas:

"Checklist para empresas revisarem o uso de IA generativa com dados pessoais."
```

Resultado esperado:

- formato visual recomendado;
- texto por lâmina;
- orientações de layout;
- ressalvas jurídicas.

### Teste da skill `business-tech-contract-review`

Use este prompt:

```text
Use a skill business-tech-contract-review para revisar as cláusulas abaixo de um contrato SaaS, considerando que represento a empresa cliente:

[cole aqui as cláusulas]
```

Resultado esperado:

- resumo executivo;
- matriz de risco;
- cláusulas críticas;
- pontos de negociação;
- sugestões de redação;
- perguntas ao cliente.

### Teste da skill `legal-ops-ai-management`

Use este prompt:

```text
Use a skill legal-ops-ai-management para criar um playbook interno de triagem de demandas consultivas trabalhistas com apoio de IA.
```

Resultado esperado:

- diagnóstico operacional;
- fluxo recomendado;
- matriz de triagem;
- pontos de uso de IA;
- pontos de revisão humana;
- critérios de qualidade.

## Fluxos reais recomendados

## Fluxo para criar conteúdo jurídico no LinkedIn

1. Use `juridico-content-strategy` para escolher tema e calendário.
2. Use `labor-law-business-content` ou `digital-law-lgpd-ai-content` para produzir o rascunho.
3. Use `legal-accuracy-review` para revisar precisão técnica.
4. Use `oab-compliance-review` para revisar ética e publicidade.
5. Use `multichannel-repurposing` para adaptar para LinkedIn, newsletter ou vídeo.
6. Use `visual-law-legal-design` se quiser transformar em carrossel ou quadro visual.

Prompt completo:

```text
Quero criar um conteúdo para LinkedIn sobre [tema].

Use este fluxo:
1. juridico-content-strategy para definir ângulo e público.
2. [labor-law-business-content ou digital-law-lgpd-ai-content] para redigir.
3. legal-accuracy-review para revisar precisão.
4. oab-compliance-review para revisar publicidade jurídica.
5. multichannel-repurposing para gerar versão LinkedIn e newsletter.

Público: [empresas/RH/jurídico interno/advogados].
Tom: técnico, claro, sóbrio e prático.
```

## Fluxo para transformar jurisprudência em conteúdo

1. Cole a ementa, notícia ou acórdão.
2. Use `case-law-to-content` para extrair tese, contexto e limites.
3. Use `legal-accuracy-review` para checar extrapolações.
4. Use `oab-compliance-review` para evitar chamada comercial.
5. Use `multichannel-repurposing` ou `visual-law-legal-design` para adaptar o formato.

Prompt completo:

```text
Use case-law-to-content para transformar a decisão abaixo em conteúdo educativo.

Depois, aplique:
- legal-accuracy-review para evitar extrapolação;
- oab-compliance-review para revisar publicidade;
- multichannel-repurposing para gerar LinkedIn, newsletter e carrossel.

Decisão/notícia:
[cole aqui]
```

## Fluxo para revisão contratual

1. Cole o contrato ou cláusulas.
2. Informe o papel do cliente: contratante, contratado, fornecedor ou cliente.
3. Use `business-tech-contract-review`.
4. Peça matriz de risco e pontos de negociação.
5. Se quiser transformar em relatório visual, use `visual-law-legal-design`.

Prompt completo:

```text
Use business-tech-contract-review para revisar este contrato.

Meu papel: [contratante/contratado/fornecedor/cliente].
Tipo de contrato: [SaaS/NDA/DPA/prestação de serviços/desenvolvimento de software].
Objetivo: matriz executiva de riscos e pontos de negociação.

Contrato:
[cole aqui]
```

## Fluxo para gestão interna do escritório

1. Escolha uma rotina: triagem, revisão de contratos, conteúdo, pesquisa, atendimento ou base de conhecimento.
2. Use `legal-ops-ai-management`.
3. Peça playbook, matriz de triagem, critérios de QA e pontos de revisão humana.

Prompt completo:

```text
Use legal-ops-ai-management para criar um playbook de [rotina].

Contexto:
- equipe: [número de pessoas];
- área: [trabalhista/digital/empresarial/contencioso/consultivo];
- problema atual: [descrever];
- ferramenta de IA disponível: Claude;
- objetivo: padronizar, ganhar produtividade e manter qualidade técnica.
```

## Boas práticas de uso

### Sempre informe o papel e o público

Uma mesma análise muda conforme o destinatário. Um conteúdo para RH não deve ter o mesmo tom de um parecer para jurídico interno. Uma revisão contratual muda se você representa contratante ou contratado.

### Sempre peça revisão de precisão

Mesmo quando o texto parecer bom, use `legal-accuracy-review` para checar tese, fonte, ressalva e extrapolação. Isso é especialmente importante em jurisprudência, LGPD, IA e temas trabalhistas com alta dependência de fatos.

### Sempre revise publicidade jurídica antes de publicar

Use `oab-compliance-review` em posts, artigos, newsletters, vídeos, carrosséis, páginas e CTAs. O objetivo é manter caráter informativo, sobriedade e evitar promessa de resultado ou captação indevida.

### Não use dados sigilosos sem cuidado

Antes de colar documentos reais, avalie sigilo, dados pessoais, dados sensíveis, confidencialidade contratual e política de segurança. Quando possível, anonimize nomes, valores, CNPJs, CPFs, números de processo e dados de clientes.

### Use as skills em cadeia

O maior ganho está na combinação. Por exemplo, uma notícia de decisão pode virar análise técnica, post de LinkedIn, newsletter e carrossel, mas deve passar por revisão jurídica e revisão OAB antes de publicação.

## Prompts mestres

### Prompt mestre para conteúdo jurídico empresarial

```text
Quero produzir conteúdo jurídico empresarial sobre [tema].

Use o pacote de skills nesta ordem:
1. juridico-content-strategy: definir ângulo, público e formato.
2. [labor-law-business-content ou digital-law-lgpd-ai-content]: criar rascunho.
3. legal-accuracy-review: revisar precisão jurídica.
4. oab-compliance-review: revisar publicidade e sobriedade.
5. multichannel-repurposing: adaptar para LinkedIn, newsletter e blog.
6. visual-law-legal-design: sugerir carrossel ou quadro visual.

Público-alvo: [informar].
Objetivo: [educar, prevenir risco, explicar decisão, gerar autoridade].
Tom: técnico, claro, sóbrio e útil.
```

### Prompt mestre para análise de decisão

```text
Quero transformar a decisão abaixo em conteúdo jurídico digital.

Use:
1. case-law-to-content para classificar a decisão, extrair tese e limites.
2. legal-accuracy-review para evitar extrapolação.
3. oab-compliance-review para revisar a linguagem.
4. multichannel-repurposing para criar LinkedIn, newsletter e roteiro de vídeo.

Não trate decisão isolada como entendimento consolidado.
Inclua ressalvas sobre caso concreto e necessidade de leitura do inteiro teor.

Texto da decisão/notícia:
[colar]
```

### Prompt mestre para contrato

```text
Quero revisar este contrato empresarial/tecnológico.

Use business-tech-contract-review.

Meu papel: [contratante/contratado/fornecedor/cliente].
Tipo de contrato: [informar].
Objetivo: identificar riscos, cláusulas críticas, pontos de negociação e redações alternativas.
Entregue em formato executivo, com matriz verde/amarelo/vermelho.

Contrato:
[colar]
```

### Prompt mestre para rotina interna

```text
Quero estruturar uma rotina interna do escritório com apoio de IA.

Use legal-ops-ai-management.

Rotina: [triagem/revisão contratual/pesquisa/conteúdo/atendimento/base de conhecimento].
Problema atual: [descrever].
Objetivo: criar playbook, checklist, pontos de revisão humana, indicadores e governança de IA.
```

## Ordem de prioridade para evoluir o pacote

Depois de instalar e testar, a evolução recomendada é:

1. Personalizar `voice-style-library`, se for criada futuramente, com exemplos reais do seu estilo.
2. Adicionar uma skill específica de petições ou contencioso trabalhista, se o objetivo incluir peças processuais.
3. Criar assets visuais editáveis em PowerPoint, Canva ou Figma para a skill de Visual Law.
4. Criar uma base de referências com decisões e temas recorrentes.
5. Criar scripts para transformar arquivos `.docx`, `.pdf` ou `.md` em insumos padronizados.

## Checklist final de instalação

- [ ] Baixar o ZIP.
- [ ] Descompactar o pacote.
- [ ] Importar cada pasta de skill separadamente no Claude.
- [ ] Testar cada skill com prompt curto.
- [ ] Testar um fluxo completo de conteúdo.
- [ ] Testar um fluxo de revisão contratual.
- [ ] Ajustar linguagem e exemplos ao seu estilo profissional.
- [ ] Definir regra interna de revisão humana.
- [ ] Definir regra de uso de dados sigilosos.
- [ ] Atualizar o pacote conforme uso real.

## Observação final

Este pacote deve ser tratado como infraestrutura de trabalho jurídico com IA. Ele ajuda a padronizar método, linguagem, revisão e produção, mas não elimina responsabilidade profissional, revisão técnica, sigilo, ética e análise individualizada.
