# Como Criar um Copilot com Fluxo de Conversa Personalizado no Copilot Studio

Este conteúdo ensina como criar um copilot com fluxo de conversa personalizado dentro do Copilot Studio, com o objetivo de compreender os melhores cenários de uso da plataforma e as considerações cruciais ao desenvolver um agente virtual.

## Pré-Requisitos

Para iniciar, é necessário:

- Ter acesso a uma conta do Microsoft 365.
- Possuir um computador, pois o Copilot Studio opera dentro desse ecossistema.

## Passos Iniciais

1. **Acesse o Copilot Studio**: Vá até [copilotstudio.com](https://copilotstudio.com) e crie um novo agente em branco.
2. **Defina o Nome e Descrição**: Durante a criação, você pode definir um nome e uma descrição para o copilot.
3. **Configuração do Prompt**: Um aspecto fundamental da criação é a configuração das instruções (o prompt), que moldam o comportamento, o tom e a linguagem do agente. É recomendável usar o inglês para melhor aproveitamento dos recursos generativos.

## Personalização de Tópicos

Após a criação do agente, o aprendizado se concentra na customização de tópicos. Isso envolve:

1. **Criação de Novos Tópicos**: Defina os tópicos que o copilot deve abordar.
2. **Frases de Gatilho**: Configure frases que iniciam esses tópicos.
3. **Personalização das Ações**: Customize as ações dentro de cada tópico.

### Respostas Generativas

Uma funcionalidade chave é a utilização de respostas generativas. Estas podem ser configuradas para buscar informações em fontes de dados e responder às perguntas dos usuários. Além disso, é possível editar o prompt em nível de tópico para refinar ainda mais o comportamento em contextos específicos.

## Personalização de Mensagens de Erro

Quando o copilot não consegue encontrar uma resposta, ele pode exibir mensagens de erro. Embora existam tópicos como "conversational boosting" e "fallback" para lidar com essas situações, com as respostas generativas ativadas, as falhas tendem a ser gerenciadas pelo "conversational boosting". A personalização dessas mensagens pode incluir:

- Informações de contato.
- Sugestões para o usuário.
- Ações avançadas, como o envio de notificações ou a integração com o Power Automate para cenários de falhas mais complexos.

## Ajuste da Qualidade e Precisão das Respostas

A qualidade e precisão das respostas generativas podem ser ajustadas nas configurações de fontes de dados:

1. **Uso de Conhecimento Geral da IA**: Habilite ou desabilite o uso do conhecimento geral da IA (atualmente GPT-4) e restrinja o copilot a usar apenas as fontes de dados configuradas.
2. **Controle do Nível de Moderação**: O nível de moderação afeta a criatividade e a precisão das respostas:
   - **Nível alto**: Prioriza respostas altamente relevantes.
   - **Nível baixo**: Permite respostas mais criativas, embora menos diretamente relacionadas.

## Configurações Gerais de IA Generativa

No Copilot Studio, existem configurações gerais de "IA generativa" que permitem definir o comportamento do agente como um todo. Essas configurações influenciam como as instruções iniciais são interpretadas e a qualidade geral das respostas.

## Conclusão

Em resumo, abrange desde a criação básica de um copilot até a personalização avançada de seu comportamento em tópicos específicos, o tratamento de erros e o ajuste da qualidade das respostas geradas por inteligência artificial.
