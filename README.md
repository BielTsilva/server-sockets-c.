# Servidor Web com Sockets em C

Este projeto é um servidor web simples desenvolvido em C utilizando sockets. Ele escuta conexões na porta 8080 e responde com uma mensagem HTTP básica para qualquer requisição recebida.

## 📌 Funcionalidades

- Aceita conexões na porta 8080.
- Lê a requisição do cliente.
- Responde com uma mensagem HTTP simples (`Hello, World!`).

## 🚀 Como executar

1. **Clone o repositório**:
   ```sh
   git clone https://github.com/BielTsilva/server-sockets-c.git
   cd server-sockets-c

    Compile o código:

gcc server.c -o server

Execute o servidor:

./server

Testando o servidor:
Abra um navegador e acesse:

http://localhost:8080

Ou use o curl no terminal:

    curl http://localhost:8080

🛠️ Requisitos

    Um compilador C (ex: gcc).
    Um sistema Unix/Linux ou WSL (para Windows).

📜 Estrutura do Código

O código segue os seguintes passos:

    Criação do socket do servidor.
    Configuração do endereço e porta.
    Vinculação (bind) do socket.
    Entrada no modo de escuta (listen).
    Aceitação de conexões (accept).
    Leitura da requisição e envio de resposta.
    Fechamento da conexão.

📌 Melhorias Futuras

    Suporte a múltiplas requisições simultâneas.
    Servir arquivos HTML estáticos.
    Adicionar logs de requisições.

Feito por @BielTsilva 🚀
