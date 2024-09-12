# Teste Dev Node JR

Este é um projeto simples de API REST desenvolvido em Node.js utilizando o framework Express.

## Descrição

O projeto consiste em um servidor que fornece uma rota para acessar informações sobre produtos. Os dados dos produtos são armazenados em um arquivo JSON.

## Funcionalidades

- Leitura de dados de produtos a partir de um arquivo JSON
- Exposição de uma rota GET `/products` para retornar todos os produtos

## Tecnologias Utilizadas

- Node.js
- Express.js
- File System (fs) para leitura de arquivos

## Como Executar

1. Certifique-se de ter o Node.js instalado em sua máquina
2. Clone este repositório
3. Navegue até a pasta do projeto
4. Execute `npm install` para instalar as dependências
5. Execute `node index.js` para iniciar o servidor
6. Acesse `http://localhost:3000/products` em seu navegador ou cliente HTTP

## Estrutura do Projeto

- `index.js`: Arquivo principal contendo a configuração do servidor e a rota
- `products.json`: Arquivo JSON contendo os dados dos produtos
