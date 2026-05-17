---
name: business-tech-contract-review
description: "Revisa contratos empresariais e tecnológicos para advogados, empresas e jurídico interno. Use para analisar SaaS, prestação de serviços, desenvolvimento de software, licenciamento, NDA, parceria, DPA, termos de uso, contratos comerciais, cláusulas de dados, propriedade intelectual, responsabilidade, rescisão e riscos negociais."
license: MIT
metadata:
  version: "1.0.0"
  language: "pt-BR"
---

# Revisão de Contratos Empresariais e Tecnológicos

## Quando usar

Use esta skill quando o usuário pedir:

- revisão de contrato empresarial;
- análise de contrato de tecnologia;
- revisão de SaaS;
- revisão de contrato de desenvolvimento de software;
- análise de NDA;
- revisão de DPA ou cláusulas de proteção de dados;
- análise de propriedade intelectual;
- revisão de cláusulas de responsabilidade, indenização, multa, SLA, rescisão ou foro;
- matriz de risco contratual;
- sugestões de negociação;
- resumo executivo para cliente, diretoria ou jurídico interno.

## Objetivo

Produzir uma revisão contratual estruturada, prática e negociável, destacando riscos jurídicos, comerciais e operacionais, sem substituir revisão final por advogado responsável e sem inventar cláusulas que não estejam no material analisado.

## Procedimento

1. Identifique:
   - tipo de contrato;
   - partes;
   - papel do usuário: contratante, contratado, fornecedor, cliente, controlador, operador, licenciante ou licenciado;
   - jurisdição aplicável;
   - setor;
   - valor estratégico;
   - grau de urgência.
2. Faça uma leitura executiva:
   - objeto;
   - obrigações principais;
   - preço e pagamento;
   - prazo;
   - responsabilidades;
   - riscos de dados;
   - riscos de propriedade intelectual;
   - rescisão;
   - solução de conflitos.
3. Classifique cada ponto como:
   - verde: aceitável ou baixo risco;
   - amarelo: negociável ou exige ajuste;
   - vermelho: risco material ou escalonamento.
4. Aplique `references/clausulas-criticas.md` para revisar cláusulas essenciais.
5. Aplique `references/matriz-risco-contratual.md` para organizar o resultado.
6. Sugira redações alternativas, quando possível.
7. Diferencie:
   - risco jurídico;
   - risco comercial;
   - risco operacional;
   - risco regulatório;
   - risco reputacional.
8. Indique pontos que exigem informação adicional.

## Formato de saída

Entregue:

1. Resumo executivo.
2. Premissas e informações faltantes.
3. Matriz de riscos.
4. Cláusulas críticas.
5. Pontos de negociação.
6. Sugestões de redação.
7. Perguntas para o cliente ou área de negócio.
8. Conclusão: aprovar, aprovar com ajustes, negociar ou não assinar sem revisão adicional.

## Regras de segurança

- Não invente cláusulas ausentes.
- Se o contrato não foi fornecido integralmente, destaque limitação da análise.
- Se houver dados pessoais, verifique necessidade de DPA, papéis de controlador/operador, suboperadores, incidente, retorno/eliminação de dados e transferência internacional.
- Se houver tecnologia, verifique propriedade intelectual, licença, código-fonte, open source, feedback, SLA, suporte, disponibilidade, reversibilidade e continuidade.
- Leia limitação de responsabilidade e indenização em conjunto.
- Marque como risco alto cláusulas que eliminem remédios essenciais, transfiram responsabilidade excessiva ou afetem ativos estratégicos.
- Não trate a revisão como parecer final quando faltarem anexos, proposta comercial, DPA, SOW, SLA ou termos incorporados por referência.

## Referências internas

Leia `references/clausulas-criticas.md` para checklist por cláusula.

Leia `references/matriz-risco-contratual.md` para formato de classificação.

Leia `references/redacoes-alternativas.md` para sugestões de redação e fallback negocial.

Leia `references/perguntas-ao-cliente.md` para levantar informações faltantes.
