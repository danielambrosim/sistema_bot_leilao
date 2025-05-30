# Instalação de Dependências
npm install node-telegram-bot-api mysql2 nodemailer bcrypt dotenv cpf-cnpj-validator cheerio axios
npm install -D typescript ts-node @types/node @types/bcrypt @types/nodemailer @types/cheerio @types/axios @types/node-telegram-bot-api nodemon

## Pacotes Principais
npm install node-telegram-bot-api mysql2 nodemailer bcrypt dotenv cpf-cnpj-validator cheerio axios


## Pacotes de Desenvolvimento
npm install -D typescript ts-node @types/node @types/bcrypt @types/nodemailer @types/cheerio @types/axios @types/node-telegram-bot-api nodemon


## Configuração do TypeScript
npx tsc --init


## Estrutura do Projeto

sistema_bot_leilao/
├── src/
│   ├── bot.ts                 // Lógica principal do bot
│   ├── db.ts                  // Conexões e queries MySQL
│   ├── mail.ts                // Envio de e-mails (nodemailer)
│   └── utils/
│       └── helpers.ts         // Funções auxiliares reutilizáveis (validações, etc.)
├── .env                       // Configurações sensíveis
├── tsconfig.json             // Configuração do TypeScript
├── package.json              // Dependências e scripts
└── README.md                 // Instruções do projeto


# Inicialização do Projeto
## Instalar Dependências
npm install


# Observações Importantes

- Agora o projeto utiliza **MySQL** como banco de dados, usando o pacote `mysql2`.
- Atualize sua variável de ambiente `DATABASE_URL` no `.env` para o formato do MySQL:
  ```
  DATABASE_URL=mysql://usuario:senha@localhost:3306/meu_banco
  ```
- O script de criação do banco está em `create-db-template.sql` e já está adaptado para MySQL.

# Commits

- fix (Commit que vão consertar bugs ou erros)
- feat (Funcionalidade nova)
- chore (mudança que não vai causar nem mudança de erro ou funcionalidade nova)
- docs (Qualquer parte da documentação do projeto)

Toda mensagem de Commit tem que completar a seguinte frase: quando for aplicado esse commit irá...

(exemplo: quando for aplicado esse commit irá... uma série de mudanças nesse arquivo)




Uso do MySQL dependendo da MÁQUINA você terá que alterar o arquivo .env para integrar ao sistema de cadastro;
