<h1 align="center">Ignite React Native - IgniteFleet</h1>

<p align="center">
  <img 
    src="https://img.shields.io/badge/React Native-0.71.8-blue" 
    alt="React Native Ver. 0.71.8"
  />
  <img 
    src="https://img.shields.io/badge/Typescript-5.0.4-blue"
    alt="Typescript Ver. 5.0.4" 
  />
   <img 
    src="https://img.shields.io/badge/Expo-48.0.6-black" 
    alt="Expo Ver. 48.0.6"
  />
  <img
    src="https://img.shields.io/badge/Ignite-2023-green" 
    alt="Ignite-2023"
  />
  <img 
    alt="License"
    src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033"
  />
</p>

<div align="center">

  ![Last commit](https://img.shields.io/github/last-commit/Jonathan-Rios/ignite-n-react-native-ignitefleet?color=4DA1CD 'Last commit') &nbsp;
  ![Repo size](https://img.shields.io/github/repo-size/Jonathan-Rios/ignite-n-react-native-ignitefleet?color=4DA1CD 'Repo size') &nbsp;
  ![Languages](https://img.shields.io/github/languages/count/Jonathan-Rios/ignite-n-react-native-ignitefleet?color=4DA1CD 'Languages') &nbsp;

</div>

<br>

<h3 align="center">Imagem prévia da aplicação: Autenticando com conta google</h3>

<div align="center">
  <img src=".github/project-preview-01.gif?style=flat" alt="Cover" width="415" height="850">
</div>

<h3 align="center">Imagem prévia da aplicação: Registrando um passeio e finalizando</h3>

<div align="center">
  <img src=".github/project-preview-02.gif?style=flat" alt="Cover" width="415" height="850">
</div> 
<br>

## 💻 Projeto
Descrição do projeto:
Essa aplicação foi desenvolvida para estudos seguindo os ensinamentos da **[Rocketseat](https://www.rocketseat.com.br/)** no curso Ignite **[Ignite](https://www.rocketseat.com.br/ignite)** .
 

O foco da aplicação foi 
* Abordar o login com OAuth2 usando o Google.
* Aplicar os conceitos de offline first.
* Utilização de RealmDB.
* Conceitos de Background Task.
* Sincronização dos dados das operações offline.
* Trabalhar com Geolocalização e Mapa.


## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ReactNative](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.dev/)
- [Realm.io](https://realm.io/)
- [Styled-Components](https://styled-components.com/)
 
 
## 🚀 Como executar

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/Jonathan-Rios/ignite-n-react-native-ignitefleet.git

$ cd ignite-n-react-native-ignitefleet
```

Para iniciá-lo, siga os passos abaixo:

Será necessário para iniciar que tenha instalado o [Expo CLI](https://docs.expo.dev/get-started/installation/)
 
```bash
# Instalar as dependências
$ expo install

# Iniciar o projeto
$ expo start
```

## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE.md) para mais detalhes.

<br />


## 📓 Anotações pessoais

<h3>Comandos utilizados</h3>

```bash

# Criando o projeto
➜ npx create-expo-app ignite-n-react-native-ignitefleet --template
✔ Choose a template: › Blank (TypeScript)

# Instalado para remover um alerta no build, referente a configuração "userInterfaceStyle": "dark", no app.json
➜ npx expo install expo-system-ui

# Instalando Styled Components
➜ npm install styled-components
➜ npm install -D @types/styled-components @types/styled-components-react-native 

# Instalando fontes
➜ npx expo install expo-font @expo-google-fonts/roboto

➜ npm install -D react-native-dotenv

➜ npm install @react-native-google-signin/google-signin

# Comando para pegar chaves do android (estando na raiz do projeto). 
# Para realizar o registro do app no Google Cloud Service e obter o ID do App
cd android && ./gradlew signingReport && cd ..

# Instalando o realm do Mongo
➜ npm install realm
➜ npm install @realm/react

# Para usarmos é necessário instalar o SVG pois não temos svg no mobile igual temos na web
➜ npm install phosphor-react-native
➜ npx expo install react-native-svg

➜ npx expo install expo-image

➜ npm install @react-navigation/native
➜ npx expo install react-native-screens react-native-safe-area-context
➜ npm install @react-navigation/native-stack
￼
# Necessário para gerar uuid, precisa importar algo no app.tsx, DOC:https://www.npmjs.com/package/react-native-get-random-values
➜ npm install react-native-get-random-values

➜ npm install dayjs

➜ npm install react-native-keyboard-aware-scroll-view       
➜ npx expo install @react-native-community/netinfo
➜ npx expo install @react-native-async-storage/async-storage

➜ npm install react-native-toast-message

# Precisa de configuração de plugins no app.json
➜ npx expo install expo-location

➜ npx expo install react-native-maps

➜ npx expo install expo-task-manager
```

<br />

<a href="https://github.com/Jonathan-Rios">
 <img src="https://github.com/Jonathan-Rios.png" width="100px;" alt="" style="border-radius:50%" />
 <br />
 <sub><b>Jonathan Rios Sousa</b></sub></a>

💠 NeverStopLearning 💠
 

[![Linkedin Badge](https://img.shields.io/badge/-Jonathan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/)](https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/) 
[![Gmail Badge](https://img.shields.io/badge/-jonathan.riosousa@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jonathan.riosousa@gmail.com)](mailto:jonathan.riosousa@gmail.com)