# ♻️ Ecoleta

É uma aplicação web/mobile que compartilha e cadastra informações sobre pontos de coletas seletivas com os usuários que desejam descartar seus diferentes tipos de resíduos.

---

## App

### 💾 Instalação e 🚀Inicialização

Faça o clone desse repositório e instale os modulos separadamente em cada pasta.

```bash
git clone git@github.com:jhortale/Ecoleta.git
cd Ecoleta
```

Instale separadamente cada pasta:

### 🧮 Backend (Ecoleta/server)

Servidor Node.js rodando Express.js e typescript com banco de dados em SQLite3.

```bash
cd Ecoleta/server
npm install
```

Após instalar as dependencia roando npm, rode os seguintes comandos para criar e popular a base de dados com os dados iniciais:

```bash
npm run knex:migrate
npm run knex:seed
```

Para inicializar o desenvolvimento:

```bash
npm run dev
```

### 💻Front-end Web (Ecoleta/web)

React.js com Typescript

```bash
cd Ecoleta/web
npm install
```

Para inicializar o desenvolvimento:

```bash
npm start
```

### 📱Front-end Mobile (Ecoleta/mobile)

React Native com Typescript utilizando Expo.

Mobile

```bash
cd Ecoleta/mobile
npm install
```

Para inicializar o desenvolvimento:

```bash
npm start
```

---

### Backend

Front-end Web

Projeto desenvolvido durante a NLW - Next Level Week oferecida pela Rocketseat. O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.
