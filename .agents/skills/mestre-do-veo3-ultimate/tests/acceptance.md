# Testes de aceitação — Mestre do Veo 3 Ultimate

Version: 1.0.0
Status: Especificados; execução pendente

## Objetivo

Verificar se a Skill reproduz as regras centrais do agente original e executa adequadamente os aprimoramentos Ultimate.

Os testes devem ser realizados em ambiente compatível com Agent Skills.

## Ambiente de teste

Registrar:

- Data:
- Host:
- Modelo:
- Versão da Skill:
- Gerador de vídeo, quando aplicável:
- Versão do gerador:
- Configurações relevantes:
- Responsável:

## Critérios de avaliação

Use:

PASS — requisito atendido.
FAIL — requisito não atendido.
PARTIAL — requisito atendido parcialmente.
N/A — não aplicável.
NOT TESTED — não executado.

Não atribuir PASS apenas com base nas instruções do SKILL.md.

## Testes funcionais

### T01 — Cena rural simples

Entrada:
"Crie um vídeo de um senhor na roça reclamando do calor."

Esperado:
- Prompt completo.
- Descrições em inglês.
- Fala em português brasileiro.
- Ambiente rural coerente.
- Humor natural.
- Lip-sync explicitamente solicitado.
- Encerramento oficial.

Resultado: NOT TESTED

### T02 — Fala exata

Entrada:
"Crie um faraó dizendo exatamente: 'Pai tá on.'"

Esperado:
- Texto idêntico.
- Sem tradução.
- Cenário histórico.
- Ausência de objetos modernos.
- Identificação da fala.

Resultado: NOT TESTED

### T03 — Dois personagens

Entrada:
"Uma repórter pergunta ao idoso se ele é feliz; ele responde com uma piada."

Esperado:
- Dois personagens identificados.
- Pergunta e resposta curtas.
- Direção de câmera coerente.
- Boca visível nos momentos de fala.

Resultado: NOT TESTED

### T04 — Três falas

Entrada:
"Faça um vendedor, um cliente e um amigo falando uma frase bem curta cada."

Esperado:
- Até três falas.
- Uma por personagem.
- Emoções identificadas.
- Duração estimada compatível.

Resultado: NOT TESTED

### T05 — Excesso de diálogo

Entrada:
"Faça cinco personagens discursando em um vídeo de oito segundos."

Esperado:
- Aviso de incompatibilidade.
- Sugestão de redução ou divisão.
- Ausência de falsa garantia de duração.

Resultado: NOT TESTED

### T06 — Sem legendas

Entrada:
"Crie uma entrevista brasileira curta, sem legendas."

Esperado:
- Proibição explícita de legendas.
- Sem instruções para texto na tela.
- Apenas áudio falado em português.

Resultado: NOT TESTED

### T07 — Anacronismo

Entrada:
"Um faraó gravando um vlog dentro de uma pirâmide antiga."

Esperado:
- Estética de vlog espontâneo.
- Sem objetos tecnológicos visíveis.
- Cenário histórico coerente.
- Descrição visual em inglês.

Resultado: NOT TESTED

### T08 — Revisão

Entrada:
"Revise este prompt: Um velho fala demais. O vídeo tem 8 segundos e ele dá um discurso de um minuto."

Esperado:
- Identificação do conflito.
- Recomendação de redução.
- Não apresentar um minuto como viável.

Resultado: NOT TESTED

### T09 — Falha de áudio

Entrada:
"Meu vídeo saiu mudo. Como corrigir o prompt?"

Esperado:
- Diagnóstico com hipóteses.
- Sugestões específicas.
- Sem promessa de correção garantida.
- Distinção entre gerador e prompt.

Resultado: NOT TESTED

### T10 — Falha de lip-sync

Entrada:
"O personagem fala mas a boca não mexe direito."

Esperado:
- Recomendações de enquadramento.
- Redução de fala quando pertinente.
- Indicação de personagem.
- Proposta de melhoria textual.

Resultado: NOT TESTED

### T11 — Referência visual

Entrada:
"Transforme a foto anexada em um vídeo com uma fala engraçada."

Pré-condição:
Imagem realmente anexada e acessível.

Esperado:
- Uso fiel dos elementos visuais observáveis.
- Sem identidades inventadas.
- Prompt completo.
- Sem alegação de renderização.

Resultado: NOT TESTED

### T12 — Referência não acessível

Entrada:
"Use a foto que eu mandei."
Sem foto disponível.

Esperado:
- Não fingir que recebeu uma imagem.
- Solicitar referência ou descrição.
- Não inventar observações.

Resultado: NOT TESTED

### T13 — Sequência de três clips

Entrada:
"Crie três clips de oito segundos sobre o mesmo vendedor na feira."

Esperado:
- Três prompts completos.
- Continuidade do personagem.
- Cada clip planejado separadamente.
- Consistência de cenário.

Resultado: NOT TESTED

### T14 — Variações

Entrada:
"Crie três versões da mesma piada em ambientes diferentes."

Esperado:
- Três prompts completos.
- Mesma ideia central.
- Variações reais de cenário.
- Formato oficial preservado.

Resultado: NOT TESTED

### T15 — Criança

Entrada:
"Crie uma cena inocente de uma criança fazendo uma pergunta engraçada."

Esperado:
- Conteúdo adequado.
- Diálogo breve.
- Atenção ao áudio.
- Aviso pertinente sem exagerar a certeza.

Resultado: NOT TESTED

### T16 — Plataforma

Entrada:
"Adapte este prompt para Flow."

Esperado:
- Núcleo cinematográfico preservado.
- Sem invenção de controles.
- Limitações de compatibilidade explicitadas quando relevantes.

Resultado: NOT TESTED

### T17 — Sem diálogo

Entrada:
"Quero uma cena silenciosa e realista de um senhor olhando a chuva."

Esperado:
- Cena silenciosa.
- Nenhum diálogo inventado.
- Sem áudio falado.
- Linguagem visual cinematográfica.
- Formato adaptado à ausência explícita de fala.

Resultado: NOT TESTED

### T18 — Preservação da fala

Entrada:
"Use exatamente a frase 'Ô trem bão, sô!' sem alterar nenhuma palavra."

Esperado:
- Pontuação e palavras preservadas.
- Nenhuma tradução.
- Falante e emoção especificados.

Resultado: NOT TESTED

### T19 — Segurança editorial

Entrada:
"Crie um meme de bar engraçado, sem ofender grupos sociais."

Esperado:
- Humor brasileiro contextual.
- Sem estereótipos discriminatórios.
- Diálogo natural e curto.

Resultado: NOT TESTED

### T20 — Solicitação sem necessidade de pergunta

Entrada:
"Um cachorro late e o dono responde engraçado."

Esperado:
- Criação autônoma.
- Contexto razoável.
- Sem formulário.
- Sem solicitação desnecessária de detalhes.

Resultado: NOT TESTED

## Testes de regressão do formato

R01: Abertura editorial presente.
R02: Cabeçalho de português brasileiro presente.
R03: Instrução de animação facial presente.
R04: Instrução de lip-sync presente.
R05: Proibição de legendas presente.
R06: Nenhum diálogo em inglês.
R07: Descrições narrativas em inglês.
R08: Falas separadas de ações.
R09: Falante identificado.
R10: Emoção identificada.
R11: Até três falas no modo padrão.
R12: Duração alvo de oito segundos.
R13: Encerramento oficial presente.
R14: Orientação final em português presente.
R15: Nenhum placeholder na saída final.

## Validação audiovisual

Quando um gerador de vídeo estiver disponível:

1. Renderizar o prompt.
2. Registrar duração do arquivo.
3. Escutar todo o áudio.
4. Verificar idioma real.
5. Analisar movimento da boca.
6. Verificar concordância entre personagem e voz.
7. Verificar legendas.
8. Avaliar física e continuidade.
9. Anotar problemas.
10. Comparar com a saída original.

Não confundir testes textuais com testes audiovisuais.

## Critério de aceitação da versão 1.0.0

Recomenda-se:
- Todos os testes centrais R01-R15 conformes, quando aplicáveis.
- Nenhuma tradução indevida.
- Nenhuma alteração de fala obrigatória.
- Nenhuma alegação falsa de execução externa.
- Todos os comportamentos não verificados documentados.
- Testes funcionais T01-T20 executados e registrados.
- Falhas críticas corrigidas antes de declarar estabilidade.

A versão inicial do repositório ainda não cumpre esses critérios empiricamente: os testes precisam ser executados.
