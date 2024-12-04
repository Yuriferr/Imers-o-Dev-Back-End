
# Imers-o-Dev-Back-End

Este é um projeto de API utilizando Node.js, Express e MongoDB para gerenciar posts e uploads de imagens. A API foi construída para fins de aprendizado e demonstração.

## Funcionalidades

- Listar posts
- Criar um novo post
- Fazer upload de imagens
- Integração com o MongoDB para armazenamento dos dados

## Pré-requisitos

- Node.js (versão >= 14.0.0)
- NPM (versão >= 6.0.0)

## Instalação

1. Clone o repositório:

```bash
  git clone <URL_DO_REPOSITORIO>
  cd <NOME_DO_DIRETORIO>
```

2. Instale as dependências:

```bash
  npm install
```

3. Configure as variáveis de ambiente:

- Crie um arquivo .env na raiz do projeto com as variáveis

A API estará disponível em http://localhost:3000.
    
## Endpoints

Listar Posts
 
- GET /posts
- Retorna todos os posts cadastrados.

Criar Post

- POST /posts
- Body (JSON):

```bash
{
  "descricao": "Descrição do post",
  "alt": "Descrição da Imagem"
}
```

Fazer Upload de Imagem

- POST /upload
- Form Data:
    - file: Arquivo de imagem para upload


## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Multer para uploads de arquivos
- Dotenv para variáveis de ambiente
## Licença

[MIT](https://choosealicense.com/licenses/mit/)


## Autor

- Desenvolvido por *Yuri Fernandes*
- [yurifernandespreto@gmail.com](mailto:yurifernandespreto@gmail.com)