Projeto de API com Node.js e MongoDB
Este é um projeto de API utilizando Node.js, Express e MongoDB para gerenciar posts e uploads de imagens. A API foi construída para fins de aprendizado e demonstração.

Funcionalidades
Listar posts
Criar um novo post
Fazer upload de imagens
Integração com o MongoDB para armazenamento dos dados
Pré-requisitos
Node.js (versão >= 14.0.0)
NPM (versão >= 6.0.0)
Banco de dados MongoDB configurado e em execução
Instalação
Clone o repositório:

bash
Copiar código
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_DIRETORIO>
Instale as dependências:

bash
Copiar código
npm install
Configure as variáveis de ambiente:

Crie um arquivo .env na raiz do projeto com as seguintes variáveis:

env
Copiar código
PORT=3000
MONGO_URI=mongodb://localhost:27017/seu-banco
Executando o projeto
Inicie o servidor de desenvolvimento com:

bash
Copiar código
npm run dev
A API estará disponível em http://localhost:3000.

Endpoints
Listar Posts
GET /posts
Retorna todos os posts cadastrados.
Criar Post
POST /posts

Body (JSON):

json
Copiar código
{
  "titulo": "Exemplo de Post",
  "descricao": "Descrição do post"
}
Fazer Upload de Imagem
POST /upload

Form Data:

file: Arquivo de imagem para upload.
Retorno:

json
Copiar código
{
  "id": "12345",
  "descricao": "Descrição do post",
  "imgUrl": "uploads/nome-da-imagem.png"
}
Tecnologias Utilizadas
Node.js
Express
MongoDB
Multer para uploads de arquivos
Dotenv para variáveis de ambiente
Licença
Este projeto está licenciado sob a licença AGPL-3.0. Veja o arquivo LICENSE para mais detalhes.

Autor
Desenvolvido por Yuri Fernandes
Email

Sinta-se à vontade para ajustar as informações específicas, como URLs de repositórios e detalhes de configuração do banco de dados. Se precisar de mais ajustes, é só avisar! 😊
