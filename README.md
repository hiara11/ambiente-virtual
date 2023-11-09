#Como fazer um bot de previsão do tempo usando a API ..........  e a biblioteca .......... pra:

<h1>o que deve ter instalado e configurado para este projeto?</h1>

1. Chave da API OpenWeatherMap: É necessário obter uma chave de API da OpenWeatherMap para acessar os dados de previsão do tempo. Você pode obter uma chave em [OpenWeatherMap API](https://openweathermap.org/api).
 
2. Chave do Bot do Telegram: Você precisa criar um bot no Telegram e obter uma chave de acesso para o seu bot. Para criar um bot, converse com o BotFather.
 
3. Bibliotecas Python: Certifique-se de que as seguintes bibliotecas Python estejam instaladas em seu ambiente:
   - telepot: Para interagir com a API do Telegram.
   - requests: Para fazer solicitações HTTP.
   - urllib3: Para manipular erros de solicitação HTTP.
   - googletrans: Para tradução de texto.
 
Você pode instalar as bibliotecas usando o pip:
```bash
pip install telepot requests urllib3 googletrans==4.0.0-rc1
```
## Configuração
Antes de executar o bot, você precisará configurar algumas variáveis no código:
 
1. Chave da API OpenWeatherMap: Substitua a variável api_key na função get_weather com a sua própria chave de API OpenWeatherMap:
 
api_key = 'SUA_CHAVE_AQUI'
 
2. Chave do Bot do Telegram: Substitua a variável TELEGRAM_BOT_KEY no final do código com a chave do seu próprio bot do Telegram:
 
TELEGRAM_BOT_KEY = 'SUA_CHAVE_AQUI'

<h2>Como usar o bot de previsão do tempo no Telegram</h2>
passo a passo:

1. Inicie uma conversa com o seu bot do Telegram.
 
2. Envie o comando /start para iniciar a interação com o bot. O bot responderá com uma mensagem de boas-vindas, pedindo que você digite o nome da cidade para a qual deseja obter a previsão do tempo.
 
3. Digite o nome da cidade desejada (em inglês) e envie a mensagem.
 
4. O bot responderá com a previsão do tempo para a cidade especificada, incluindo a descrição do tempo em português e a temperatura em graus Celsius.

