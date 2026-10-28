# Matriz de comparação — Agente original vs Skill Ultimate

Version: 1.0.0
Status: Aguardando execução

## Finalidade

Comparar a experiência do agente original Mestre do Veo3 com a Skill independente.

Use rigorosamente o mesmo pedido, sem alterações, em ambos os ambientes.

## Protocolo de comparação

1. Registrar versão ou identificação dos ambientes.
2. Selecionar um caso.
3. Enviar a mesma entrada ao agente original.
4. Salvar a resposta integral.
5. Enviar a entrada idêntica ao agente com Skill.
6. Salvar a resposta integral.
7. Avaliar os critérios.
8. Registrar diferenças e falhas.
9. Repetir cada caso ao menos três vezes, se possível.
10. Documentar a variabilidade entre resultados.

Evitar ajustes manuais durante uma comparação.

## Escala de pontuação

0 = Não atende.
1 = Atende de modo muito limitado.
2 = Parcial.
3 = Adequado.
4 = Muito bom.
5 = Excelente.

NV = Não verificado.

Avaliar separadamente o original e a Skill.

## Dimensões

| Código | Critério | Peso |
|--------|----------|------|
| C01 | Cobertura funcional | 15% |
| C02 | Precisão | 10% |
| C03 | Qualidade | 15% |
| C04 | Consistência | 10% |
| C05 | Formato | 10% |
| C06 | Preservação da especialidade | 15% |
| C07 | Autonomia | 5% |
| C08 | Tratamento de referências | 5% |
| C09 | Utilidade prática | 10% |
| C10 | Funcionalidades avançadas | 5% |

Total: 100%

Nota ponderada = soma(nota / 5 × peso).

Calcule somente para critérios efetivamente avaliados e informe a cobertura dos critérios.

## Matriz de casos

| Caso | Nível | Agente original | Skill Ultimate |
|------|-------|----------------|----------------|
| T01 — Cena rural | Simples | NV | NV |
| T02 — Fala exata | Simples | NV | NV |
| T03 — Entrevista | Intermediário | NV | NV |
| T04 — Três falas | Intermediário | NV | NV |
| T05 — Excesso de diálogo | Complexo | NV | NV |
| T06 — Sem legendas | Simples | NV | NV |
| T07 — Cena histórica | Intermediário | NV | NV |
| T08 — Revisão | Intermediário | NV | NV |
| T09 — Áudio ausente | Complexo | NV | NV |
| T10 — Lip-sync defeituoso | Complexo | NV | NV |
| T11 — Referência de imagem | Complexo | NV | NV |
| T12 — Referência ausente | Simples | NV | NV |
| T13 — Três clips | Complexo | NV | NV |
| T14 — Variações | Intermediário | NV | NV |
| T15 — Criança | Intermediário | NV | NV |
| T16 — Adaptação Flow | Complexo | NV | NV |
| T17 — Cena silenciosa | Intermediário | NV | NV |
| T18 — Diálogo literal | Simples | NV | NV |
| T19 — Humor seguro | Intermediário | NV | NV |
| T20 — Autonomia | Simples | NV | NV |

## Registro individual

Para cada caso, preencher:

ID:
Entrada exata:
Data:
Modelo original:
Modelo da Skill:
Versão da Skill:
Saída original armazenada em:
Saída da Skill armazenada em:

Cobertura funcional original:
Cobertura funcional Skill:

Precisão original:
Precisão Skill:

Qualidade original:
Qualidade Skill:

Consistência original:
Consistência Skill:

Formato original:
Formato Skill:

Preservação da especialidade original:
Preservação da especialidade Skill:

Autonomia original:
Autonomia Skill:

Tratamento de referências original:
Tratamento de referências Skill:

Utilidade prática original:
Utilidade prática Skill:

Funcionalidades avançadas original:
Funcionalidades avançadas Skill:

Diferenças observadas:
Problemas:
Melhoria sugerida:
Resultado geral:

## Funcionalidades documentadas e não testadas

O agente original possui regras explícitas para:
- Prompt em inglês.
- Diálogo em português.
- Lip-sync.
- Duração curta.
- Separação das falas.
- Humor brasileiro.
- Cenários históricos.
- Avisos de risco.

Essas são funções documentadas, não medições de desempenho.

## Funcionalidades Ultimate adicionadas

Exigem validação independente:
- Revisão sistemática.
- Diagnóstico técnico.
- Análise de referências.
- Storyboard multiclips.
- Estimativa de duração.
- Controle de continuidade.
- Adaptação entre plataformas.
- Auditoria estruturada.

Não marcar uma funcionalidade como preservada do original quando ela foi adicionada nesta versão.

## Critérios de equivalência

Equivalência funcional só pode ser considerada após:
- Execução da matriz.
- Cobertura dos casos centrais.
- Comparação das respostas.
- Análise de falhas relevantes.
- Repetição suficiente para avaliar consistência.

Equivalência absoluta não deve ser declarada.

## Relatório final

Data:
Quantidade de casos executados:
Quantidade de testes PASS:
Quantidade de testes PARTIAL:
Quantidade de testes FAIL:
Quantidade de testes NOT TESTED:
Nota ponderada original:
Nota ponderada Skill:
Falhas críticas:
Recursos não verificados:
Recomendação:
Responsável:

## Conclusão inicial

O repositório fornece uma reconstrução funcional documentada, com recursos Ultimate adicionais.

O comportamento real continua pendente de testes no host e nos geradores de vídeo.

Nenhuma nota numérica foi atribuída sem evidência.
