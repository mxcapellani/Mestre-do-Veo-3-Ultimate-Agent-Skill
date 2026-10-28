# Compatibilidade com geradores de vídeo

Version: 1.0.0

## Princípio de portabilidade

O Mestre do Veo 3 Ultimate produz prompts textuais cinematográficos. O formato padrão independe de API e não exige controle programático do gerador de vídeo.

A Skill não deve afirmar compatibilidade garantida sem teste no serviço de destino.

## Veo / Veo 3

Objetivo:
- Geração de cenas realistas.
- Diálogo em português brasileiro.
- Ênfase em lip-sync.
- Clips curtos.

Estratégia:
1. Utilizar o formato oficial.
2. Manter poucas falas.
3. Identificar o falante.
4. Descrever ações fisicamente viáveis.
5. Evitar cortes excessivos.
6. Verificar o resultado visual e sonoro.

A duração disponível, o suporte ao áudio e a forma de controlar o vídeo dependem do produto e versão utilizados.

## Google Flow

Objetivo:
- Utilizar o prompt cinematográfico na interface de geração disponível.

Estratégia:
1. Manter a descrição em inglês.
2. Preservar falas brasileiras nas aspas.
3. Separar ações e diálogos.
4. Configurar opções de interface somente quando realmente disponíveis.
5. Testar o resultado.

Não inventar nomes de campos, configurações de duração ou recursos da interface.

## Gemini

Objetivo:
- Utilizar as capacidades de geração de vídeo disponíveis na experiência do usuário.

Estratégia:
1. Usar o formato completo quando o serviço aceitar prompts de vídeo.
2. Preservar indicações de idioma.
3. Limitar a complexidade da cena.
4. Verificar se a conta e a experiência oferecem geração de vídeo.

A presença da Skill não desbloqueia acesso a serviços ou modelos.

## Outros geradores

Condição mínima:
O sistema deve aceitar instruções textuais de cena.

Para áudio sincronizado:
O gerador também deve oferecer recursos adequados de geração ou integração audiovisual.

Se gerar apenas vídeo silencioso, o prompt não poderá forçar a criação de falas.

## Matriz de validação externa

| Recurso | Estado inicial |
|--------|----------------|
| Entrada textual | Depende da plataforma |
| Diálogo português brasileiro | Não testado |
| Lip-sync natural | Não testado |
| Duração de até 8 segundos | Não testado |
| Respeito à ausência de legendas | Não testado |
| Consistência entre clips | Não testado |
| Fidelidade de personagens | Não testado |

Esses estados devem ser atualizados após testes práticos.

## Procedimento de teste de plataforma

1. Selecionar o gerador e registrar sua versão.
2. Escolher um prompt do diretório examples.
3. Executar a geração.
4. Registrar duração real.
5. Confirmar se o áudio está em português.
6. Inspecionar sincronização labial.
7. Identificar cortes de fala.
8. Verificar legendas e textos acidentais.
9. Registrar alterações de personagens.
10. Documentar o resultado.

## Falhas conhecidas por categoria

### Áudio ausente

Possíveis hipóteses:
- Gerador sem recurso de áudio.
- Modo de geração inadequado.
- Duração insuficiente.
- Limitação ou falha do serviço.

### Diálogo traduzido

Possíveis hipóteses:
- Priorização incorreta da instrução de idioma.
- Texto descritivo confundido com fala.
- Comportamento específico da plataforma.

### Sincronização labial ruim

Possíveis hipóteses:
- Muitas falas.
- Falante não identificado.
- Boca fora de quadro.
- Troca de planos muito rápida.
- Limitação do modelo de vídeo.

### Legendas geradas

Possíveis hipóteses:
- Interpretação equivocada da fala.
- Legendas automáticas da ferramenta.
- Comportamento não controlável apenas pelo prompt.

## Atualização de compatibilidade

Antes de declarar suporte confirmado, consulte a documentação atual da ferramenta e execute ao menos um teste representativo.

Registre:
- Data.
- Modelo.
- Produto.
- Prompt.
- Configurações utilizadas.
- Resultado.
- Evidências.

Não transforme hipóteses em afirmações de compatibilidade.
