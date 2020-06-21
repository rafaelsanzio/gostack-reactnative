<h1 align="center">
  Challenge GoStack React Native 🚀
  <p align="center">
  <img src="https://img.shields.io/badge/tech-front--end-green" />

  <a href="https://reactnative.dev/">
    <img src="https://img.shields.io/badge/framework-reactnative-blue" />
  </a>

  <a href="https://github.com/Rocketseat">
    <img src="https://img.shields.io/badge/source-rocketseat-blueviolet" />
  </a>
  </p>
</h1>

 Primeiro desafio em [React Native](https://reactnative.dev/ "React Native") da [RocketSeat](https://rocketseat.com.br/ "RocketSeat"), passado no bootcamp GoStack 12.
**Frontend** (Mobile) para a **[API em NodeJS](https://github.com/rafaelsanzio/gostack-nodejs "API em NodeJS")**

A proposta é simples: criar elementos visuais para gerenciar repositórios (Fakes), sendo possível adicionar e remover respositórios e dar likes nos repositórios


## Getting Started ▶️
- **Passo 1**: git clone do projeto gostack-reactnative
```bash
  # Navegando até a pasta do projeto
  $ cd gostack-reactnative

  # Instalando todas as depêndencias necessárias
  $ npx react-native init mobile

  # Em dispositivos iOS
  $ npx react-native run-ios

  # Em dispositivos Androi d
  $ npx react-native run-android
  $ npx react-native start 
 
 #Obs: 
  #No iOS o Metro Bundler inicia sozinho. 
  #No Android, é necessário iniciá-lo manualmente.
```

## Arquitetura ⚙️

- O código **JavaScript** é enviado para o packager (`Metro Bundler`), que fica monitorando estes códigos JS e gera um bundle. Este bundle é enviado então para a `Bridge`. A bridge (ou ponte) é responsável por transformar o código JS obtido em **Java (Android)** e **Objective-C (iOS)**.

 <p align="center">
 	<img src="https://user-images.githubusercontent.com/18368947/85234276-8c892380-b3e2-11ea-9d00-b4452e71b835.png" />
 </p>
 
## ReactNative ❌ ReactJS

### Elementos
 - Diferente do **ReactJS**, no **React Native** não utilizamos elementos do HTML (como `div`, `h1`, etc). Ao invés disso, utilizamos elementos do próprio React Native. Elementos do mesmo também não possuem valor semântico, ou seja, não possuem um significado (diferente do HTML, em que um footer, por exemplo, indica um rodapé)

 - Elementos do próprio **React Native** são, por exemplo,  a `View`, que é substitui os "containers" do HTML (`div`, `footer`, `header`, `main`, `aside`, `section`, etc), o `Text`, que substitui os elementos de texto do HTML (`p`, `span`, `strong`, `h1`, `h2`, etc).
 
 ### Estilização
 - Diferente do **ReactJS** em que podemos utilizar diretamente arquivos `.css`, o **React Native** possui um elemento para a criação de estilização, denominado `StyleSheet`, o que permite realizar a estilização direto em arquivos `.js`. 

- No **React Native**, todos os componentes possuem por padrão `display: flex`, o que permite o uso de `flex-box`.

  ##### Exemplo:
 <p align="center">
 	<img src="https://user-images.githubusercontent.com/18368947/85234706-b3952480-b3e5-11ea-803d-d518d3fbc630.png" />
 </p>
 
## Considerações :congratulations:
- Projeto desenvolvido no Bootcamp - GoStack da [RocketSeat](https://rocketseat.com.br/ "RocketSeat")  by:

- <img width="20px" src="https://img.icons8.com/fluent/96/github.png" /> [Rafael Sanzio](https://github.com/rafaelsanzio "Rafael Sanzio")
 
- <img width="20px" src="https://img.icons8.com/color/2x/linkedin.png" /> [Rafael Sanzio](https://www.linkedin.com/in/rafael-sanzio-012778143/ "Rafael Sanzio")
