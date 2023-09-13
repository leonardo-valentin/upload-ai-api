# upload-ai-api

Uma API de backend desenvolvida com Node.js, Fastify, Prisma, API REST e TypeScript.

## Descrição

Este projeto é uma API de backend que faz um upload de um arquivo de video, gera transcrições de vídeo para audio
e com base nisso gera sugestões de títulos e descrições para um video do Youtube.
Ela foi desenvolvida usando tecnologias modernas, incluindo Node.js, Fastify, Prisma e TypeScript.

## Tabela de Conteúdo

- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Configuração](#configuração)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Instalação

Certifique-se de ter o Node.js instalado em seu sistema. Em seguida, siga os passos abaixo:

1. Clone este repositório: 
git clone https://github.com/leonardo-valentin/upload-ai-api.git
2. Navegue até o diretório do projeto:
cd seu-repositorio
3. Instale as dependências:
npm install
(ou pnpm, yarn, etc)
4. Configure o banco de dados de acordo com as instruções em [Configuração](#configuração).
5. Inicie o servidor:
pnpm run dev

Explicação da estrutura do projeto. Por exemplo:

- `src/`: Contém os arquivos do código-fonte.
  - `lib/`: Modelos de dados usando Prisma e conexão com a API do OpenAI.
  - `routes/`: Definições de rotas.
  - `middlewares/`: Middlewares personalizados.
- `prisma/`: Arquivos do banco de dados.
- `migrations/`: As migrations com as tabelas de prompts e videos.
- `tmp/`: Os videos já transcritos.

## Configuração

1. Crie um arquivo .env
   - Crie a variável que conecta ao banco de dados: DATABASE_URL="caminho"
   - Coloque a chave de conexão com a API do OpenAI: OPENAI_KEY="key"  


## Contribuição

Contribuições são bem-vindas! Siga estas etapas:

1. Faça um fork do projeto.
2. Crie uma branch com uma descrição clara da sua alteração: `git checkout -b minha-alteracao`.
3. Faça as alterações e commit: `git commit -m 'Minha alteração'`.
4. Faça o push para o seu fork: `git push origin minha-alteracao`.
5. Abra um Pull Request explicando suas alterações.

## Projeto desenvolvido durante a NLW IA da rocketseat 💜
