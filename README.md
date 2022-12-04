<p align="center">
  <img alt="NLW Copa" src="https://github.com/rocketseat-education/nlw-copa-ignite/blob/main/.github/logo.svg" />
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=NLW&message=10&color=F7DD43&labelColor=202024" alt="NLW 10 - Copa" />
  <a href="LICENSE"><img  src="https://img.shields.io/static/v1?label=License&message=MIT&color=F7DD43&labelColor=202024" alt="License"></a>
</p>

<img src="https://github.com/rocketseat-education/nlw-copa-ignite/blob/main/.github/web.png">

## 💻 Projeto

**NLW Copa** é um projeto da Rocketseat onde construimos uma aplicação de um **Bolão para a Copa do Mundo de 2022**. Essa aplicação é responsável por criar os grupos dos bolões, listar os bolões, entrar em um bolão, etc. Utilizando tecnologias como: **React** para Web, **React Native** para Mobile e **NodeJS** para o Server.

## ✨ Tecnologia

- [TypeScript](https://www.typescriptlang.org/)
- [React](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)

## 🚀 Como executar

Em todos os projetos, ao acessar a pasta, é preciso baixar os pacotes com o gerenciador de sua preferencia.

Acesse a documentação de cada projeto:

# Backend como executar 🚀

- Instale os pacotes com `npm install`.
- Faça uma copia do arquivo `.env.example` para `.env` e altere caso necessário.
- Execute `npx prisma migrate dev` para rodar as migrations. (Esse comando também já vai executar as seeds)
- Execute `npm run dev` para iniciar o servidor.

# Web como executar 🚀

**Para que esse projeto funcione corretamente, é preciso estar com o servidor rodando.**

- Instale os pacotes com `npm install`.
- Execute `npm run dev` para iniciar o cliente web.

# Mobile como executar 🚀

**Para que esse projeto funcione corretamente, é preciso estar com o servidor rodando.**

- Instale os pacotes com `npm install`.
- Criar o app no google para poder ter acesso ao OAuth (<https://docs.expo.dev/guides/authentication/#google>)
- Faça uma copia do arquivo `.env.example` para `.env` e preencha corretamente.
- Alterar o endereço do arquivo `src/services/api.ts` colocando o IP da máquina.
- Execute `npx expo start` para iniciar o servidor do Expo.

## 🔖 Layout

Você pode visualizar o layout do projeto através do link abaixo:

- [Layout](https://www.figma.com/community/file/1169028343875283461)

Lembrando que você precisa ter uma conta no [Figma](http://figma.com/).

## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  Feito com 💜 by Rocketseat
</p>
