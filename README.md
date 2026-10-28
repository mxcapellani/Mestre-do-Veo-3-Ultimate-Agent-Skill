# 🎬 Mestre do Veo 3 Ultimate

**Agent Skill independente para engenharia de prompts cinematográficos hiper-realistas, com falas em português brasileiro e foco em vídeos curtos.**

Version: 1.0.0  
Language: Portuguese (Brazil) / English  
License: MIT

## Visão geral

Mestre do Veo 3 Ultimate reconstrói a especialidade observável do agente Mestre do Veo3 em uma Skill portátil, utilizável em ambientes compatíveis com Agent Skills.

Seu propósito é transformar ideias simples ou roteiros em prompts detalhados para geradores como Veo 3, Gemini e Flow, priorizando:

- Descrições cinematográficas em inglês.
- Falas exclusivamente em português brasileiro.
- Sincronização labial natural.
- Personagens e cenários hiper-realistas.
- Humor brasileiro, memes e situações cotidianas.
- Coerência histórica e social.
- Vídeos de até oito segundos.
- Ausência de legendas e textos sobrepostos.
- Respostas completas e prontas para uso.

Esta Skill gera prompts textuais. Não renderiza vídeos de forma autônoma.

## Funcionalidades originais preservadas

1. Identidade Mestre do Veo3.
2. Abertura editorial original.
3. Formato cinematográfico padronizado.
4. Descrições de cena em inglês.
5. Diálogos em português brasileiro.
6. Indicação obrigatória de falante e emoção.
7. Instruções específicas de lip-sync.
8. Direção de câmera e iluminação.
9. Tratamento de sons ambientes.
10. Restrições de até oito segundos.
11. Máximo padrão de três falas curtas.
12. Humor informal brasileiro.
13. Adequação de cenários históricos.
14. Avisos sobre possíveis bloqueios.
15. Alerta para possíveis problemas com áudio infantil.
16. Encerramento oficial e orientação de uso.

Preservação significa reprodução das regras disponíveis para auditoria, não comprovação de equivalência de comportamento.

## Melhorias Ultimate

- Seleção automática de modo de trabalho.
- Revisão de prompts existentes.
- Estimativa de duração do diálogo.
- Diagnóstico de falhas de áudio e lip-sync.
- Análise de referências acessíveis.
- Criação de variações independentes.
- Planejamento de múltiplos clips.
- Controle de continuidade de personagens.
- Auditoria de formatos.
- Tratamento de solicitações incompletas.
- Validação de coerência histórica.
- Adaptação cautelosa entre plataformas.
- Checklist interno de qualidade.
- Separação entre hipóteses e resultados verificados.

## Estrutura

mestre-do-veo3-ultimate/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── .gitignore
└── .agents/
    └── skills/
        └── mestre-do-veo3-ultimate/
            ├── SKILL.md
            ├── references/
            │   └── platforms.md
            ├── examples/
            │   └── prompts.md
            └── tests/
                ├── acceptance.md
                └── comparison-matrix.md

## Pré-requisitos

Obrigatório:

- Assistente ou agente com suporte a instruções de Skills.
- Capacidade de ler o arquivo SKILL.md.
- Modelo de linguagem capaz de seguir instruções multilíngues.

Opcional:

- Ferramenta de análise de imagens.
- Leitura de roteiros ou documentos.
- Gerador de vídeo para renderização.
- Ferramentas de consulta externa para documentação atualizada.
- Git para versionamento e publicação.

Não são exigidas chaves de API ou credenciais para usar a Skill como gerador textual de prompts.

## Instalação

### Opção 1 — Skill no projeto

Clone o repositório na raiz do projeto que deve disponibilizar a Skill:

git clone https://github.com/SEU-USUARIO/mestre-do-veo3-ultimate.git

O diretório clonado contém:

.agents/skills/mestre-do-veo3-ultimate/SKILL.md

Se o host descobrir automaticamente o caminho .agents/skills, a Skill poderá ser carregada conforme suas regras de descoberta.

A localização e o mecanismo de ativação variam entre hosts. Confirme a documentação do ambiente utilizado.

### Opção 2 — Instalação em projeto existente

Copie o diretório:

.agents/skills/mestre-do-veo3-ultimate/

para:

SEU-PROJETO/.agents/skills/mestre-do-veo3-ultimate/

Mantenha o nome SKILL.md exatamente como está.

### Opção 3 — Carregamento manual

Quando não houver descoberta automática, forneça o conteúdo de SKILL.md como instruções ao seu agente.

Esse método reproduz as regras textuais, mas não garante paridade com sistemas que implementam Skills nativamente.

## Uso rápido

Exemplo 1:

"Crie um prompt Veo 3 com um senhor na roça dizendo: 'Cê é doido, fi!'"

Exemplo 2:

"Faça um repórter entrevistando um casal de idosos com uma resposta engraçada."

Exemplo 3:

"Transforme esta cena em um prompt cinematográfico de até oito segundos."

Exemplo 4:

"Revise meu prompt e corrija a sincronização labial."

Exemplo 5:

"Crie três clips conectados mantendo a mesma personagem."

## Modos operacionais

| Modo | Finalidade |
|------|------------|
| Criação direta | Gerar uma cena a partir de ideia simples |
| Diálogo obrigatório | Preservar falas exatamente |
| Histórico | Construir cenas coerentes com uma época |
| Meme/bar/zap | Criar humor brasileiro espontâneo |
| Revisão | Melhorar prompts existentes |
| Diagnóstico | Identificar causas possíveis de falhas |
| Referências | Extrair elementos de materiais disponíveis |
| Variações | Criar versões alternativas |
| Plataforma | Ajustar a redação para um gerador |
| Storyboard | Planejar múltiplos clips |
| Auditoria | Avaliar conformidade textual |

## Formato de resposta

O prompt padrão contém:

1. Abertura editorial.
2. Cabeçalho original de idioma e lip-sync.
3. Instruções cinematográficas.
4. Descrição do ambiente em inglês.
5. Descrição de personagens e movimentos em inglês.
6. Diálogos curtos em português brasileiro.
7. Indicação explícita de personagem e emoção.
8. Encerramento oficial.
9. Orientação final de utilização.

## Testes

Os testes estão em:

.agents/skills/mestre-do-veo3-ultimate/tests/

Execute os mesmos pedidos no agente original e na nova Skill.

Avalie:
- Cobertura funcional.
- Precisão.
- Formato.
- Coerência visual.
- Fidelidade ao diálogo.
- Preservação da especialidade.
- Utilidade prática.
- Tratamento de referências.
- Autonomia.
- Funcionalidades avançadas.

Não assuma equivalência antes da comparação.

Consulte tests/acceptance.md e tests/comparison-matrix.md.

## Atualizações

Para atualizar uma instalação baseada em Git:

git pull --ff-only

Caso a Skill tenha sido copiada manualmente, substitua os arquivos pela versão desejada e execute novamente os testes de regressão.

Antes de atualizar:
1. Consulte CHANGELOG.md.
2. Faça backup das personalizações locais.
3. Verifique alterações de comportamento.
4. Execute os testes de aceitação.
5. Compare as saídas principais.

Use tags semânticas para identificar versões, por exemplo v1.0.0.

## Limitações conhecidas

- A Skill não garante áudio nem lip-sync perfeito.
- Oito segundos é uma meta de roteiro, não garantia de duração.
- A interpretação de imagens exige suporte visual no host.
- Análise de vídeo exige ferramentas adequadas no host.
- Não verifica automaticamente os resultados do gerador externo.
- O suporte a português e áudio varia conforme a plataforma.
- Não há garantia de que um prompt funcione em qualquer versão futura de Veo ou Flow.
- O comportamento do agente original ainda precisa de comparação empírica.
- A identidade editorial preservada não constitui prova independente de autoria ou afiliação oficial.
- Preços, políticas de cobrança e restrições externas podem mudar.

## Auditoria de proveniência

A versão 1.0.0 foi desenvolvida a partir das regras funcionais disponíveis nesta conversa.

Classificação:

- Documentado: regras explícitas do agente original.
- Adicionado: melhorias projetadas para esta Skill.
- Não verificado: funcionalidades dependentes de testes.

Não houve acesso independente a configurações privadas, arquivos ocultos ou credenciais do agente original.

## Segurança e privacidade

Não adicione credenciais, arquivos pessoais ou dados sensíveis ao repositório.

Respeite os termos de uso das ferramentas de geração de vídeo.

Se uma referência contiver pessoas reais, evite inferir informações pessoais ou construir representações enganosas potencialmente prejudiciais.

## Contribuições

Consulte CONTRIBUTING.md.

## Licença

MIT. Consulte LICENSE.

A licença do repositório não altera direitos sobre marcas, nomes, materiais ou textos de terceiros. A autorização para publicar materiais de origem externa deve ser verificada pelo responsável pelo projeto.
