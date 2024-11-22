# IAvoos - Bot de Pesquisa de Voos no Telegram

Este é um bot desenvolvido para o Telegram que simula a busca de passagens aéreas com base na origem, destino e data fornecidos pelo usuário. O bot é capaz de interpretar mensagens em linguagem natural e retornar resultados simulados.

## Funcionalidades

- **Reconhecimento de linguagem natural** para identificar:
  - Origem
  - Destino
  - Data da viagem
- **Flexibilidade** para entender mensagens em diferentes formatos, como:
  - "Quero ir para Salvador dia 25 saindo de Cuiabá."
  - "Vou para Fortaleza no dia 25/12 partindo de São Paulo."
- **Validação de datas**:
  - Apenas datas do dia atual ou no futuro são aceitas.
- **Retorno de resultados simulados** de voos com duração e preço.

## Tecnologias Utilizadas

- **Python 3.10+**
- **Bibliotecas Python**:
  - `python-telegram-bot`: Integração com a API do Telegram.
  - `dateparser`: Para interpretar datas informadas pelo usuário.
  - `regex`: Para capturar padrões textuais.
  - `nest_asyncio`: Permite rodar loops assíncronos no ambiente.
  - `random`: Simula resultados de voos.

## Pré-requisitos

Antes de rodar o bot, você precisa garantir que os seguintes itens estão instalados no ambiente:

- **Python 3.10+**
- **Pacotes necessários**:
  ```bash
  pip install python-telegram-bot dateparser nest_asyncio --upgrade
  ```
## Token do Telegram Bot

1. Crie um bot no Telegram usando o **BotFather**:
   - Acesse o Telegram e inicie uma conversa com o BotFather.
   - Use o comando `/newbot` para criar um novo bot.
   - Siga as instruções e anote o **Token de Acesso** fornecido.

2. No arquivo principal do bot (geralmente `bot.py`), substitua a variável `TELEGRAM_TOKEN` pelo token fornecido pelo BotFather:
   ```python
   TELEGRAM_TOKEN = 'SEU_TOKEN_AQUI'
    ```
3. ## Como Rodar

### Clone o repositório:
```bash
git clone https://github.com/seu-usuario/IAvoos.git
cd IAvoos
```
### Instale as dependências:
```bash
pip install -r requirements.txt
```
Configure o Token do Bot:
Abra o arquivo principal (geralmente bot.py) e atualize a variável:
TELEGRAM_TOKEN = 'SEU_TOKEN_AQUI'

Execute o bot:
```bash
python bot.py
```
Inicie a interação no Telegram:
Procure pelo nome do seu bot no Telegram.
Envie o comando /start para iniciar a conversa.
