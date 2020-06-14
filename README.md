<h1 align="center">
  <img src="https://res.cloudinary.com/eliasgcf/image/upload/v1590249783/fastfeet/logo_erpvwm.svg" alt="Logo" width="250px">
</h1>

<h3 align="center">
	React Native Application for FastFeet project
</h3>

<p align="center">
  A fast way to manage delivery companies!
</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/EliasGcf/fastfeet-mobile?color=%237D40E7">

  <a href="https://www.linkedin.com/in/eliasgcf/" target="_blank" rel="noopener noreferrer">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-elias%20gabriel-%237D40E7">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/EliasGcf/fastfeet-mobile?color=%237D40E7">

  <a href="https://github.com/EliasGcf/fastfeet-mobile/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliasGcf/fastfeet-mobile?color=%237D40E7">
  </a>

  <a href="https://github.com/EliasGcf/fastfeet-mobile/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/EliasGcf/fastfeet-mobile?color=%237D40E7">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/EliasGcf/fastfeet-mobile?color=%237D40E7">
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

</br>

<p align="center">
  <img alt="Layout" src="https://res.cloudinary.com/eliasgcf/image/upload/v1592159394/fastfeet/layout-mobile_f5znq1.gif">
</p>

## 🚚 About the project

This is a React Native client that will be used by the **delivery man** for the FastFeet company.

Using the mobile client, you have some features:

- Start the delivery
- View delivery information
- View your all deliveries
- Manage the profile
- Finish the delivery by sending confirmation photo of the recipient's signature
- Create information about a problem with delivery

Link to project layout: [Project Mobile Layout](https://xd.adobe.com/view/a5d56d7d-c1d4-48a8-70ce-8b77f5f417a5-d3e4/grid)

To see the api, click here: [FastFeet Rest API](https://github.com/EliasGcf/fastfeet-api)<br />
To see the mobile client, click here: [FastFeet Web](https://github.com/EliasGcf/fastfeet-web)

## 🚀 Technologies

Technologies that I used to develop this mobile client

- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Redux](https://redux.js.org/)
- [Redux-Saga](https://redux-saga.js.org/)
- [Redux Persist](https://github.com/rt2zz/redux-persist)
- [React Navigation](https://reactnavigation.org/)
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [UnForm](https://unform.dev/) [💜](https://rocketseat.com.br/)
- [Reactotron](https://github.com/infinitered/reactotron)
- [Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## 💻 Getting started

### Requirements

- Have this application's [API](https://github.com/EliasGcf/fastfeet-api) running

**Clone the project and access the folder**

```bash
$ git clone https://github.com/EliasGcf/fastfeet-mobile.git && cd fastfeet-mobile
```

**Follow the steps below**

```bash
# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.js' have the IP to your API

# If you are going to emulate with android, run this command
# Be sure to have the emulator open
$ yarn android

# If you are going to emulate with ios, run this command
$ yarn ios
```

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork EliasGcf/fastfeet-mobile
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url && cd fastfeet-mobile

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜&nbsp; by Elias Gabriel 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/eliasgcf/)
