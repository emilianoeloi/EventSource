# Push Stream

Choose your language: [English](README.en.md)

Este projeto demonstra o uso de HTTP Push Stream (também conhecido como Server-Sent Events ou SSE) para enviar mensagens de um servidor para um cliente em tempo real. O projeto consiste em três partes:

1. **Servidor:** Um servidor Node.js que envia mensagens aleatórias para qualquer cliente conectado a cada três segundos.
2. **Cliente:** Um script de cliente JavaScript que se conecta ao servidor e ouve as mensagens.
3. **Interface web:** Uma interface de usuário simples construída com HTML e CSS que exibe as mensagens recebidas e o status da conexão.

## Arquivos do Projeto

- `server.js`: Este é o script do servidor Node.js. Ele usa o módulo 'http' para criar um servidor HTTP e o módulo 'node-uuid' para gerar IDs únicos para as mensagens.
- `index.html`: Este é a interface do usuário. Ele contém um pouco de HTML e CSS para estrutura e estilo, além de algum JavaScript para se conectar ao servidor e ouvir as mensagens.
- `package.json`: Este arquivo contém as dependências do projeto Node.js.
- `.gitignore`: Este arquivo informa ao Git quais arquivos ou diretórios ele deve ignorar.
- `README.md`: Este arquivo.

## Rodando o Projeto

Primeiro, certifique-se de que você tenha Node.js instalado em sua máquina.

Para instalar as dependências do projeto, navegue até o diretório do projeto em seu terminal e execute:

```bash
npm install
```

Para iniciar o servidor, execute:

```bash
node server.js
```

Depois de iniciar o servidor, abra o arquivo `index.html` em seu navegador para ver a interface do usuário. Ela deverá se conectar automaticamente ao servidor e começar a exibir as mensagens recebidas.

## Requisitos

- Node.js: O servidor é construído com Node.js. Certifique-se de tê-lo instalado em sua máquina para executar o servidor.
- Navegador moderno: A interface do usuário usa JavaScript moderno, então é melhor visualizá-la em um navegador moderno, como o Google Chrome ou Firefox.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar um bug ou gostaria de adicionar uma nova funcionalidade, sinta-se à vontade para criar uma issue ou pull request.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.


## Referências

1. [A simple Swift client library for the Server Sent Events (SSE)](https://github.com/inaka/EventSource)
2. [How to get HttpRequestMessage with PushStreamContent in .net core backend](https://stackoverflow.com/questions/60259375/how-to-get-httprequestmessage-with-pushstreamcontent-in-net-core-backend)
3. [push-stream](https://github.com/push-stream/push-stream)
