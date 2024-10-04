
# Bot de Busca de Voos no Telegram

## Descrição do Projeto

Este projeto implementa um bot de Telegram para auxiliar os usuários a encontrarem voos com base em comandos de linguagem natural. O bot permite que o usuário forneça informações sobre o destino e a data do voo em uma mensagem simples, e ele processa essas informações para fornecer uma resposta estruturada.

O bot utiliza a biblioteca **spaCy** para o processamento de linguagem natural (NLP) e a identificação de entidades como datas e cidades. Além disso, **dateparser** é utilizado para lidar com a extração de datas em formatos diversos, permitindo maior flexibilidade ao usuário na especificação das datas de viagem.

## Funcionalidades

- Processamento de mensagens em linguagem natural para extração de informações sobre destino e data de voos.
- Reconhecimento de cidades e destinos geográficos com o uso do spaCy.
- Identificação de datas em diversos formatos com o uso do dateparser.
- Respostas interativas e personalizadas com base nas informações fornecidas.

## Tecnologias Utilizadas

- **Python**: Linguagem principal de desenvolvimento.
- **spaCy**: Biblioteca de processamento de linguagem natural para identificar entidades como cidades.
- **dateparser**: Biblioteca para interpretação de datas em texto livre.
- **Telegram Bot API**: Integração com a API do Telegram para permitir a comunicação com os usuários.
- **asyncio**: Para lidar com a natureza assíncrona do bot.
- **Python-telegram-bot**: Interface de fácil uso para criar e gerenciar o bot no Telegram.
