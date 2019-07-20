## Erros comuns de iniciantes, em JavaScript!
```
Erro de sintaxe 
});
^
SyntaxError: Unexpected end of input
```
R: Seu código tem um erro em algum lugar. Isso é impossível de solucionar sem o código completo, pois o erro pode estar em qualquer lugar (na verdade, a pilha de erros geralmente informa que está no final do código).
O truque a seguir é um salva-vidas, então preste atenção: seu editor de código está tentando ajudá-lo. Seja qual for o editor que você esteja usando (exceto o notepad ++. Exe. Não use o notepad ++!), Clicar em qualquer (e quero dizer qualquer) caractere especial, como parênteses, colchetes, chaves, aspas duplas e simples, realçará automaticamente o aquele que combina com isso. A imagem abaixo mostra isso: cliquei na chave na parte inferior, ela mostra a que está no topo, destacando-a. Aprenda isso e como diferentes funções e manipuladores de eventos "se parecem".
```
Cannot find module discord.js
```
R: para resolver esse erro é simples, primeiro vá até o terminal do Visual Studio Code, segundo digite npm i -s discord.js para ele salvar na package.json. e deu, problema resolvido
OBS: erro de module é fácil de resolver, pois caso ele n esteja instalado na pasta node_modules. ele não irá funcionar pois vc n instalou.
caso queira instalar todos os módulos que você não tenha instalado em seu bot. a espera, esqueci de uma coisa. bom caso der esse erro em seu bot Error: Cannot find module './config.json', conste assim na sua `bot.js` ou `index.js` 
```js
const config = require('./config.json') // Ele irá constar, e localizar o código da token prefix entre outras que vc colocou na config
```

```
Erro ao iniciar o bot quando digiste node.
```
R:Bom possivel mente os erros poder ser esses aki abaixo.
Nome da pasta com letra Maiúscula
Nome da pasta com caractere diferente
npm init não atualizado, pois deve ter alterado o arquivo de inicialização do seu bot.
Entre outros...

```
 throw err; // Unhandled 'error' event
    ^

Error [ERR_UNHANDLED_ERROR]: Unhandled error. (ErrorEvent {
  target:
   WebSocket {
     _events:
      [Object: null prototype] {
        message: [Function],
        open: [Function],
        error: [Function],
        close: [Function] },
     _eventsCount: 4,
     _maxListeners: undefined,
     readyState: 2,
     protocol: '',
     _binaryType: 'nodebuffer',
     _closeFrameReceived: false,
     _closeFrameSent: false,
     _closeMessage: '',
     _closeTimer: null,
     _closeCode: 1006,
     _extensions: {},
     _receiver: null,
     _sender: null,
     _socket: null,
     _isServer: false,
     _redirects: 0,
     url: 'wss://gateway.discord.gg/?v=6&encoding=json',
     _req: null },
  type: 'error',
  message: 'read ECONNRESET',
  error:
   { Error: read ECONNRESET
       at TLSWrap.onStreamRead (internal/stream_base_commons.js:162:27) errno: 'ECONNRESET', code: 'ECONNRESET', syscall: 'read' } })
    at Client.emit (events.js:186:17)
    at WebSocketConnection.onError (C:\Users\\user\3D Objects\tft bot\node_modules\discord.js\src\client\websocket\WebSocketConnection.js:374:17)
    at WebSocket.onError (C:\Users\\user\3D Objects\tft bot\node_modules\ws\lib\event-target.js:128:16)
    at WebSocket.emit (events.js:197:13)
    at ClientRequest.req.on (C:\Users\user\3D Objects\tft bot\node_modules\ws\lib\websocket.js:568:15)
    at ClientRequest.emit (events.js:197:13)
    at TLSSocket.socketErrorListener (_http_client.js:397:9)
    at TLSSocket.emit (events.js:197:13)
    at emitErrorNT (internal/streams/destroy.js:82:8)
    at emitErrorAndCloseNT (internal/streams/destroy.js:50:3)
```
R:Bom, esse erro não tens como resolver ~~possivelmente podes ter como resolver~~. bom esse erro é por causa da Conectividade da API do discord.


Bom esse foi o guia de erros comuns de iniciantes, caso queira que eu add outro erro comun aqui no guia. me chame no discord ou me mencione la no servidor do lab negro
_Post publicado por: Ｄｅｆａｌｔ#0001 - (ID: 587446735815573514 )_
