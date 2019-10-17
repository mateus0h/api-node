# Passos para criação de um novo projeto em Node Js

### 1 - Express
  - Primeiramente instale o express com yarn add;

### 2 - Sucrase | Nodemon -D
  - Instale ambos para somente unidade de desonvolvimento yarn add -D,
  apos a instalação do sucrese passa-se a usar import e export nos arquivos .js;

### 3 - Criação do arquivo Nodemon.json
  - Crie o arvivo e adicione o json: execMap.
  - Adicione o script "dev" no package.json.

### 4 - Configurar o debug do VS Code;
  - Alterar as propriendades do lauch.json ( request e protocol);
  - adicione um novo script "dev:debug" no packege.json.

### 5 - Config to Sequelize:
  - Orm, sequelize att create -> sql;
  - Migrations, controle de versão para db; att, del, new;

### 6 - Config to EsLint:
  - yarn -D;
  - eslint --init.
  - Remover package-lock.json e rodar o yarn.
  - config rules in .eslintrc.

### 7 - Config to Prettier
  - Yarn add prettier eslint-confi-prettier eslint-plugin-prettier  -D
  - config to extends, plugins and rules to .eslintrc.
  - create to .prettierrc.
  - use yarn eslint --fix src --ext .js para corrigir tudo de uma vez.

### 8 - Config to .EditorConfig.
  - É uma extensão do vs.
  - gerar o .editorconfig  nos arquivos.

### Config to sequelize and sequelize-cli -D
  - Create and config to .sequelizerc

### Add to Pg and Pg-hstore:
